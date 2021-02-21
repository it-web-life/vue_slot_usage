<template>
  <div class="block">
    <h3>Example1: propsで渡す従来の書き方</h3>
    <p>こんにちは、{{ username }}さん</p>
  </div>
</template>

<script>
export default {
  name: 'ExampleChild',
  props: ['username']
}
</script>

<style scoped>
  .block {
    border: 1px solid #dedede;
    margin-bottom: 20px;
  }
</style>
