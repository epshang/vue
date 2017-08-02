<template>
  <div>
    {{ msg }}
  </div>
</template>

<script>
export default {
  props: {
    slides: {
      type: Array,
      default: []
    }
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  mounted (){
    console.log(this.slides)
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
