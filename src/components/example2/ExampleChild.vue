<template>
  <div class="block">
    <slot>
      <p>デフォルトの表示です</p>
    </slot>
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
