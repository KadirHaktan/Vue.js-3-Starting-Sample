<template>
  <form>
    <div class="input-group form-group">
      <div class="input-group-prepend">
        <span class="input-group-text"><i class="fas fa-user"></i></span>
      </div>
      <input type="text" class="form-control" placeholder="username" />
    </div>
    <br/>
    <div class="input-group form-group">
      <div class="input-group-prepend">
        <span class="input-group-text"><i class="fas fa-key"></i></span>
      </div>
      <input type="password" class="form-control" placeholder="password" />
    </div>
    <br/>
    <div class="row align-items-center remember">
      <input type="checkbox" />Remember Me
    </div>
    <br/>
    <div class="form-group">
      <input type="submit" value="Login" class="btn float-right login_btn" />
    </div>
  </form>
</template>

<script>
export default {
  name: "LoginBodyForm",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.input-group-prepend span{
width: 50px;
height: 40px;
background-color: #FFC312;
color: black;
border:0 !important;
}

input{
outline: 0 0 0 0;
box-shadow: 0 0 0 0;

}

.remember{
color: white;
}

.remember input
{
width: 20px;
height: 20px;
margin-left: 15px;
margin-right: 5px;
}

.login_btn{
color: black;
background-color: #FFC312;
width: 100px;
}

.login_btn:hover{
color: black;
background-color: white;
}

</style>
