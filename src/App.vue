<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
    <SignupForm/>
  </div>
  <router-view/>
</template>

<script>
import SignupForm from "./components/SignupForm.vue"
export default {
  name: "App",
  components: {SignupForm}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body{
  margin: 0%;
  background: #eee;
}

</style>
