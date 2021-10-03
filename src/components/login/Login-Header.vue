<template>
  <div class="card-header">
    <h3>Sign In</h3>
    <div class="d-flex justify-content-end social_icon">
      <span><i class="fab fa-facebook-square"></i></span>
      <span><i class="fab fa-google-plus-square"></i></span>
      <span><i class="fab fa-twitter-square"></i></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LoginHeader',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.social_icon span{
font-size: 60px;
margin-left: 10px;
color: #FFC312;
}

.social_icon span:hover{
color: white;
cursor: pointer;
}

.card-header h3{
color: white;
}

.social_icon{
position: absolute;
right: 20px;
top: -45px;
}
</style>
