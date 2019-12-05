<template>
  <div>
      <Header></Header>
  </div>
</template>

<script>
import Header from './Header'

export default {
  name: 'Index',
  components: {
      Header
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
