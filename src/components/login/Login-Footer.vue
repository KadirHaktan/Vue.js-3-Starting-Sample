<template>
  <div class="card-footer">
    <div class="d-flex justify-content-center links">
      Don't have an account?<a href="#">Sign Up</a>
    </div>
    <div class="d-flex justify-content-center">
      <a href="#">Forgot your password?</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "LoginFooter",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.links{
color: white;
}

.links a{
margin-left: 4px;
}
</style>
