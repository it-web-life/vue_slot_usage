<template>
  <div class="block">
    <ExampleChild>
      <template #title>
        <h3>Example８: slotを#で省略して記載する方法 (v-slot: を # にする)</h3>
      </template>
      <template #description>
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
