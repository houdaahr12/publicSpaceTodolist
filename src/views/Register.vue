<template>
  <div class="register">
    <h1>Register</h1>
    <!-- Registration Form -->
    <form>
      <div>
        <label for="name">Name:</label>
        <input type="text" id="name" placeholder="Enter your name" />
      </div>
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Enter your email" />
      </div>
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" placeholder="Create a password" />
      </div>
      <button type="submit">Register</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Register",
};
</script>
