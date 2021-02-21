<template>
  <div class="block">
    <ExampleChild>
      <template v-slot:[example]>
        <h3>Example７: slot名を動的に変化させる</h3>
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
  },
  data() {
    return {
      example: 'title'
    }
  }
}
</script>
