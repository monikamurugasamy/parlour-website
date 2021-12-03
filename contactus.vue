<template>  
<div calss ="da">     
        <h1> WHEN YOU VISIT US </h1>
        <p> When visiting The Beauty Parlour, we recommend parking on 100 Street, south of Whyte Avenue. There are many free parking options available for you there: angle parking, residential parking, and beside the Church are all free with no time restraints. You also have the convenient option of paid parking directly on Whyte avenue via EPark. Parking is free after 6pm.
         
        </p> <br> <br>
        <img src="@/assets/call.jpg" style="width:150px;height:150px;">
        <p> <router-link to="/CONTACTINFO"> CONTACT INFO </router-link></p>
     <router-view />
 
</div>
</template>

<script>
    export default {
      name: 'components' ,
      data()
      {
          
      } 
    }
</script>

