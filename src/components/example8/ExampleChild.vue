<template>
  <div class="block">
    <slot name="title"></slot>
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
