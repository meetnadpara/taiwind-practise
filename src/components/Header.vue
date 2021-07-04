<template>
  <div class="my-7 justify-center container mx-auto">

<div class="justify-center md:flex md:justify-between  items-center bg-red">
  <div class="justify-center pb-6 md:pb-0">  
  <img src="@/assets/logo.svg" class="ml-3 md:ml-0">  
  </div>
  

  <div class=" items-center">

    <ul class="justify-self-center md:flex items-center">
      <li class="px-4 pb-4 md:pb-0">
        <a class="" href="#">About</a>
      </li>
      <li class="px-4 pb-4 md:pb-0">
        <a class="" href="#">Feature</a>
      </li>
      
      <li class="px-4 pb-4 md:pb-0">
        <a class="" href="#">Pricing</a>
      </li>

      <li class="px-4 pb-4 md:pb-0">
        <a class="" href="#">Testimonials</a>
      </li>

      <li class="px-4 pb-4 md:pb-0">
        <a class="" href="#">Help</a>
      </li>
    </ul>
  </div>
   <div class="md:flex md:justify-end items-center" >
    <!-- <div class="collapse navbar-collapse navbar-nav mr-auto">   -->
      <div class=" font-bold pb-4 md:pb-0">Sign In</div>
      <button class="button px-15 md:ml-8 pb-6 md:pb-0" type="submit"><span>Sign Up</span></button>
  
  </div>
</div>
  </div>
</template>

<script>
export default {
 
}
</script>


<style scoped lang="scss">
.button {
  width: 140px;
  height: 46px;
  font-size: 16px;
  font-weight: 700;
  color: red;
  border: 1px solid red;
  border-radius: 23px;
  cursor: pointer;
  outline: none;
  padding:5px;
  }

  .button:hover{
  color: white;
  background-color:red;
  }
  
  ul li{
  font-family: Verdana, sans-serif;
  text-align: start;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 13px;
}

</style>
