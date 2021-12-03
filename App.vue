<template>

<div class="main2">
     <ul>
         <li> <router-link style="text-decoration:none; white;" to="/">HOME </router-link> </li>
         <li> <router-link style="text-decoration:none; white;" to="/About">ABOUT </router-link> </li>
         <li> <router-link style="text-decoration:none; white;" to="/makeup">MAKEUP DETAILS</router-link> </li>
         <li> <router-link style="text-decoration:none; white;" to="/contactus">CONTACT</router-link> </li>
         <li> <router-link style="text-decoration:none; white;" to="/Login">LOGIN </router-link> </li>
     </ul>
</div>


  <router-view />
</template>

<script>

export default {
  name: 'App',
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  height: 300px;
}


</style>
