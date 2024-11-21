<template>
  <div class="login">
    <h1>Login</h1>
    <!-- Login Form -->
    <form>
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email" />
      </div>
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" placeholder="Enter your password" />
      </div>
      <button type="submit">Login</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Login",
};
</script>
