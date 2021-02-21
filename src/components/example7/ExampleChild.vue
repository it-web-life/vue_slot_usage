<template>
  <div class="block">
    <slot name="title"></slot>
    <p>[]を使ってslot名を動的に変化させることが可能です。</p>
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
