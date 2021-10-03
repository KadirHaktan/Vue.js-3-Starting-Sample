<template>
  <div class="card-body">
    <LoginBodyForm />
  </div>
</template>

<script>
import LoginBodyForm from "./Login-Body-Form.vue";
export default {
  name: "LoginBody",
  components: {
    LoginBodyForm,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
