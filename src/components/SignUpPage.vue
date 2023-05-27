<template>
  <div>
    <h1>Sign Up</h1>
    <div class="username">
      <p>Username</p>
      <input type="text" placeholder="Username" />
    </div>
    <div class="username">
      <p>Password</p>
      <input type="password" placeholder="Password" />
    </div>
    <div class="username">
      <p>Confirm Password</p>
      <input type="password" placeholder="Confirm Password" />
    </div>
    <p>Already have an account? Login <a href="">here</a></p>
  </div>
</template>
<script>
export default {
  name: "SignupPage",
};
</script>
<style scoped>
* {
  background: url("https://www.pixelstalk.net/wp-content/uploads/images2/Teal-Background.png");
}
</style>
