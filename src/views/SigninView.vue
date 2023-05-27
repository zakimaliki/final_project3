<template>
  <div class="login">
    <h1>Sign In</h1>
    <div class="username">
      <p>Username</p>
      <input type="text" placeholder="Username" />
    </div>
    <div class="username">
      <p>Password</p>
      <input type="password" placeholder="Password" />
    </div>
    <p style="font-weight: 600">
      Don't have an account? Register
      <a href=""><router-link to="/signup">Here</router-link></a>
    </p>
    <button>Submit</button>
  </div>
</template>
<script>
export default {
  name: "SigninView",
};
</script>
<style scoped>
* {
  background: url("https://www.pixelstalk.net/wp-content/uploads/images2/Teal-Background.png");
  justify-content: space-between;
  align-content: center;
  text-align: center;
  color: white;
  font-family: sans-serif;
}

.login {
    padding-top: 50px;
    padding-bottom: 50px;
}

h1 {
  font-weight: bold;
}

.username p {
  font-weight: 550;
  margin-right: 220px;
}

.username input {
  width: 300px;
  border: none;
  background: lightgray;
  height: 30px;
  border-radius: 5px;
}

.username {
  line-height: 0.2;
  padding-bottom: 20px;
  padding-top: 20px;
}

.username input::placeholder {
  text-align: left;
}

a {
  background: none;
}

a:hover {
  color: #088178;
  text-decoration: none;
}

button {
  width: 120px;
  height: 40px;
  border-radius: 10px;
  border: none;
  color: white;
  font-family: sans-serif;
  font-weight: bold;
  background: #088178;
  outline: none;
}
</style>
