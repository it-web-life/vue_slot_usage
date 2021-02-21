<template>
  <div class="block">
    <ExampleChild>
      <template v-slot:example="slotProps">
        <h3>Example５: スロットプロパティを使って、子→親に値を渡す方法</h3>
        <p>こんにちは、{{ slotProps.user.lastName }} {{ slotProps.user.firstName }}さん</p>
        <p>年齢：{{ slotProps.age }}歳</p>
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
