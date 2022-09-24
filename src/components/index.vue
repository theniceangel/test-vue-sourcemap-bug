<template>
  <div class="hello">
    <inner-index />
  </div>
</template>
<script>
  /* eslint-disable */
  import InnerIndex from './inner/index.vue'
  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    },
    data () {
      return {
        Halo: 'heiheihei'
      }
    },
    created () {
      debugger
    },
    components: {
      InnerIndex
    },
    methods: {
      sayHello () {
        console.log(this.Halo)
      }
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
