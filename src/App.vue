<template>
  <div id="app">
    <router-link to="/">HOME</router-link> |
    <router-link to="/vmodel">V-Model</router-link> |
    <router-link to="/von">von</router-link> |
    <router-link to="/vbind">vbind</router-link> |
    <router-link to="/prop">Prop</router-link>

    <br /><br />
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
