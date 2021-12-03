<template>
<body bgcolor="">
  <div class="login">
<form @submit="submitform" action="Home.vue">
<div class="container">
  <h1>LOGIN</h1>
    <p>Please fill in this form to create an account.</p>
    <hr>
     <div v-for="actor in actors" :key="actor.name">
    <h5>Username:<input type="text" placeholder="username" id="name" required>{{actor.name}}</h5>
    <h5 v-for="email in actor.emailid" :key="email">Email:<input type="text" placeholder="email-id" id="email" required>{{email}}</h5>
    <h5 v-for="passwd in actor.password" :key="passwd">Password:<input type="password" placeholder="password" id="password" required>{{passwd}}</h5>
    <h5 v-for="repasswd in actor.repassword" :key="repasswd">Repeat password:<input type="password" placeholder="Repeat password" id="repassword" required>{{preasswd}}</h5>
    <hr>
    <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>
 
    <p> <router-link to="/About"> Login </router-link></p>
     <router-view />
     </div>
</div>
</form>
  </div>
</body>

</template>
 
<script>
export default {
  name: 'App',
  data()
  {
    return{
      actors:[
         {
         username:'',
         emailid:[''],
         password:[''],
         repassword:['']
         }
       ]
  }
},
methods:{
submitForm(event)
{
event.preventDefault()
console.log('Form values',this.formValues)
alert("Logged")

}
}
 
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
}
h1{
  font-style:italic;
  font-size:40px ;
  color: rgb(96, 38, 204);
}
.container {
  padding: 16px;
  
  
}
 
/* Overwrite default styles of hr */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
 
.registerbtn {
  background-color:black;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 15%;
  opacity: 0.9;
  
}
 
.registerbtn:hover {
  opacity: 1;
}
 
/* Add a blue text color to links */
a {
  color: rgb(98, 30, 255);
}
 


.login{
  border: 3px solid rgb(25, 15, 61);
  border-radius: 5px;
  padding: 1.5rem;
  width: 600px;
  height:600px;
  margin-left: auto;
  margin-right: auto; 
  text-align: left;
  overflow: hidden;
  position: relative;
  background-color:#FFB6C1;
}
</style>
 