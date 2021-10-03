<template>
    <div class="card">
      <LoginHeader/>
      <LoginBody/>
      <LoginFooter/>
    </div>
</template>

<script>
import LoginHeader from "./Login-Header.vue"
import LoginBody from "./login-body/Login-Body.vue"
import LoginFooter from "./Login-Footer.vue"
export default {
  name: 'Login',
  components:{
    LoginHeader,
    LoginBody,
    LoginFooter
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.card{
height: 370px;
margin-top: auto;
margin-bottom: auto;
margin-right: auto;
margin-left: auto;
width: 500px;
background-color: rgba(0,0,0,0.5) !important;
}
</style>
