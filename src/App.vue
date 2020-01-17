<template>
  <div id="app">
    <TopHeader />
    <b-container fluid class="bv-example-row">
      <!-- Content here -->

      <router-view />
    </b-container>
  </div>
</template>

<script>
import TopHeader from "./components/TopHeader";

export default {
  components: {
    TopHeader
  }
};
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
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
