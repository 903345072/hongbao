<template>
  <div>
      <div class="header">
       <div class="header-img">
           <img :src="img" alt="">
       </div>
       <div class="user-info"></div>
       <div class="act"></div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      img: "http://localhost:8081/static/123.png"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .header{
        width: 100%;
        height: 2rem;
        display: flex;
    }
    .header-img{
        width: 20%;
    }
</style>
