<template>
  <div class="home">
    <div class="nav">
      <login></login>
      <router-view/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from '../components/Login.vue'

export default {
  name: 'home',
  components: {
    Login
  }
}
</script>

<style scoped>
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

