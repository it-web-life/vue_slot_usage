<template>
  <div class="block">
    <slot name="example" :user="user" :age="age"></slot>
  </div>
</template>

<script>
export default {
  name: 'ExampleChild',
  data() {
    return {
      user: {
        firstName: '太郎',
        lastName: '山田'
      },
      age: 20
    }
  }
}
</script>

<style scoped>
  .block {
    border: 1px solid #dedede;
    margin-bottom: 20px;
  }
</style>
