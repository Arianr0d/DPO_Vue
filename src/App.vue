<template>
   <div id="app">
      <div id="nav">
         <router-link to="/" style="margin-right: 15px;">Home</router-link>    
         <router-link to="/unitconversion">Задание 1</router-link>
      </div>
      <router-view class="router"/>
   </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }

  }
}
</style>
