<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      
      <router-link to="/about">About</router-link>

    </div>
    <router-view/>
  </div>
</template>

<style>
*{
  padding: 0;
  margin: 0;
}
#app{
  text-align: center
}
#nav a{
  font-size: 20px;
}
</style>
