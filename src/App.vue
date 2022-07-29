
<template>
  <div id="app">
  <h2> Simple SPA </h2>
    <div id="nav">
      <router-link to="/">Home</router-link> 
      <router-link to="/about">About</router-link>
      <router-link to="/contact"> Contact </router-link>
    </div>
    <router-view />
  </div>
</template>
<style>


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;   
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

body {
  background-color: #fff;    /* ennen  #FFCC00*/
  padding: 20px;
  margin: 0;
}

#nav {
  background-color: #42b983; /*  Navigointi menu */ /* #111*/
  padding: 0;
}

#nav a {
  color: #FFF;
  font-weight: bold;
  text-decoration: none;
  padding: 20px;
  display: inline-block;
}

#nav a.router-link-exact-active {
  color: #fff; /* #42b983; */
}

h2{
  font-family: sans-serif;
}

.vue-logo{
  text-align: center;
  margin-top: 75px;
}

</style>

