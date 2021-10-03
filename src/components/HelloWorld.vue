<template>
    <div class="d-flex justify-content-center h-100">
    <Login/>
  </div>
  
</template>

<script>
import Login from "./login/Login.vue"
export default {
  name: "HelloWorld",
  components:{
    Login
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
