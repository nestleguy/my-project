<template>
    <div>
      <h2>Login</h2>
      <button @click="login">LoginPage</button>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      login() {
        // logic to login the user
        this.$router.push('/homePage');
      }
    }
  }
  </script>
  
  <style scoped>
  /* Add your styles here */
  </style>
  