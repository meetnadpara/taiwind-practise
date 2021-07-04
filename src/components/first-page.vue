<template>

  <div class="mt-20 container mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 justify-between gap-6 items-center">
      <div class="items-center">
       
        <h1 class="my-5">Want anyting to be easy with <span>LaserVPN.</span></h1>
        <p>Provide a network for all your needs with ease and fun using <span>LaserVPN</span> discover interesting features from us.</p>  
        <div class="mt-10 flex"><button class="button">Get Started</button></div>
      
    </div>
    
      <div class="">
       
        <img src="@/assets/Illustration1.svg" class="object-scale-down">
      
    </div>
  </div>
  <div class="mt-20 sm:grid sm:grid-cols-3 sm:h-28 sm:shadow-md">
      <div class="justify-center items-center my-6 border-r-2 flex">
      <div class="mr-5 ">
          <img src="@/assets/user.svg" class="object-scale-down">
        </div>

        <div class="">
          <div class="my-1">
          <h3>90+</h3>
        </div>
        <div class="my-1">
         <p>Users</p>
        </div>
        </div>
      </div>
   
<div class="justify-center items-center my-6 border-r-2 flex">
      <div class="mr-5">
          <img src="@/assets/user.svg" class="object-scale-down">
        </div>

        <div class="">
          <div class="my-1">
          <h3>90+</h3>
        </div>
        <div class="my-1">
         <p>Users</p>
        </div>
        </div>
      </div>
   
   <div class="justify-center items-center my-6 border-r-2 flex">
      <div class="mr-5">
          <img src="@/assets/Server.svg" class="object-scale-down">
        </div>

        <div class="">
          <div class="my-1">
          <h3>90+</h3>
        </div>
        <div class="my-1">
         <p>Users</p>
        </div>
        </div>
      </div>
   



</div>
</div>
  
</template>

<script>
export default {

  data () {
    return {
     

}
}
}

</script>


<style scoped lang="scss">

div h1{
  font-weight : 800 ;
  color : black ;
  font-family: 'Rubik', sans-serif;
  font-size: 45px;
  text-align: start;
}
div h3{
  
  font-weight: 800;
  color : black ;
  font-family: 'Rubik', sans-serif;
  font-size: 18px;
  text-align: start;
}

div p{
  font-family: Verdana, sans-serif;
  text-align: start;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
}

.button {
  width: 200px;
  height: 45px;
  font-size: 13px;
  font-weight: 500;
  color: white;
  background-color: red;
  border: none;
  border-radius: 5px;
  box-shadow: 0px 5px 15px 0px red ;
  cursor: pointer;
  outline: none;
  }

</style>
