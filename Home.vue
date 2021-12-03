<template>
<div class="main">
  <div class="image">
    <b><p style="font-family:papyrus; font-size:40px;">Women Beautilocks</p></b><img src="@/assets/makeup.jpg" style="width:200px; height:230px;"> 
  </div>
</div>

<div class="main1">
    <p>“Elegance comes from being as beautiful inside as outside.” “Make-up can only make you look pretty on the outside but it doesn’t help if you’re ugly on the inside. Unless you eat the make-up.” “A smile is the best makeup any girl can wear.”</p>
</div>
</template>
<script>
export default {
  name: 'Home' ,      
  
}
</script>
<style lang ="css">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 100px;
}
.body
{
  background-color:rgb(14, 1, 14);
}
.kongu{
 padding: 10px;
  background:rgb(255, 145, 0);
  height:2000%;
  width: 2%;
  text-align: center;
}
.main
{
  padding: 10px;
  background:orange;
  color: rgb(19, 2, 2);
  font-weight: 900;
  top: 0px;
  height: 400px;
  size-adjust: align-self;
}
.main1
{
  padding: 10px;
  background:rgb(245, 221, 3);
  color: rgb(8, 0, 0);
  font-weight: 900;
  top: 0px
}
.main2
{
  padding: 15px;
  background-color: violet;
  }
.main2 ul
{
  text-decoration: none;
  list-style-type: none;
  display: inline-flex;
}
.main2 ul li
{
  text-decoration: none;
  padding-right: 50px;
  color: rgb(156, 245, 12);
  font-weight: 700;
  text-decoration-color: azure;
}
.main.image{
  height: 100px;
  width: 100px;
}
</style> 