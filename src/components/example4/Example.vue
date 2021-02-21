<template>
  <div class="block">
    <ExampleChild>
      <h4>デフォルトのパーツ１</h4>
      <template v-slot:title>
        <h3>Example4: 名前付きslotのname="default"の使い方(name="default"は省略が可能)</h3>
      </template>
      <div><span>デフォルトのパーツ2</span></div>
      <template v-slot:description>
        <p>こんにちは、山田さん</p>
      </template>
      <p>デフォルトのパーツ3</p>
      <p>name="default"は省略が可能。名前付きslot以外のslot部分がまとめて結合されてdefaultのslot部分に表示されます。</p>
    </ExampleChild>
  </div>
</template>

<script>
import ExampleChild from './ExampleChild.vue'

export default {
  name: 'Example',
  components: {
    ExampleChild
  }
}
</script>
