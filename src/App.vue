<template>
  <div id="app">
    <div id="nav">      
      <router-link to="/VehicleEntryForm">Vehicle Entry Form</router-link> |
      <router-link to="/GridOfVehicles">Grid of vehicles</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
 .btn-vue{
    background: #53B985;
    color: #31485D;
    font-weight: bold;
}
html, body, .container-table{
  height: 100%;
  background-color:  #bce5d0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;  
}
#nav {
  padding: 30px;


a { font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.btn-primary{
    background: #53B985;
    color: #31485D;
    font-weight: bold;
}
</style>
