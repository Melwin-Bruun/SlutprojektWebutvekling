<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/Chuck_Noris_Jokes">Chuck Noris Jokes</router-link> |
    <router-link to="/Trupms_quotes">Trupms quotes</router-link> |
    <router-link to="/Advice_For_you">Advice For you</router-link> |
  </div>./components/landing_page.vue
  <router-view/>
</template>

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
