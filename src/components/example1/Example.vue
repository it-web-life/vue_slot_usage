<template>
  <div>
    <ExampleChild :username="'山田'"></ExampleChild>
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
