<template>

  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/newView">New view</router-link> |
    <router-link to="/user/1">User 1</router-link> |
    <router-link to="/user/2">User 2</router-link> |
    <router-link to="/user/3">User 3</router-link> |
  </div>

  <router-view/>
</template>

<script>

export default {
  data() {
    return {

    }
  }
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
