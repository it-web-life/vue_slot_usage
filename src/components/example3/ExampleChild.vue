<template>
  <div class="block">
    <slot name="title"></slot>
    <p>v-slotを使って名前付きコンポーネントを使用しています</p>
    <slot name="description"></slot>
  </div>
</template>

<script>
export default {
  name: 'ExampleChild',
}
</script>

<style scoped>
  .block {
    border: 1px solid #dedede;
    margin-bottom: 20px;
  }
</style>
