<template>
  <div class="block">
    <ExampleChild>
      <h3>Example2: slotでテンプレート自体を渡す方法</h3>
      <p>こんにちは、山田さん</p>
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
