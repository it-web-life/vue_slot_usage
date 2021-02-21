<template>
  <div class="block">
    <ExampleChild>
      <template v-slot:title>
        <h3>Example3: 名前付きslotで値を渡す方法</h3>
      </template>
      <template v-slot:description>
        <p>こんにちは、山田さん</p>
      </template>
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
