<template>
  <!-- <nav>
     <router-link to="/">Home</router-link> 
     <router-link to="/about">About</router-link>
  </nav> -->
  <router-view/>
</template>

<style>
#app {

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}
body{
  margin: 0;
  padding: 0;
  @import url('https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');
  font-family: 'Abril Fatface', cursive;

  /* font-family: 'Poppins', sans-serif; */

  /* font-family: 'Ubuntu', sans-serif; */
}

nav {

  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
