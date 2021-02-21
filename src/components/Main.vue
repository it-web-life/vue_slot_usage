<template>
  <div class="wrap">
    <Example1></Example1>
    <Example2></Example2>
    <Example3></Example3>
    <Example4></Example4>
    <Example5></Example5>
    <Example6></Example6>
    <Example7></Example7>
    <Example8></Example8>
  </div>
</template>

<script>
import Example1 from './example1/Example.vue'
import Example2 from './example2/Example.vue'
import Example3 from './example3/Example.vue'
import Example4 from './example4/Example.vue'
import Example5 from './example5/Example.vue'
import Example6 from './example6/Example.vue'
import Example7 from './example7/Example.vue'
import Example8 from './example8/Example.vue'

export default {
  name: 'Main',
  components: {
    Example1,
    Example2,
    Example3,
    Example4,
    Example5,
    Example6,
    Example7,
    Example8,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
