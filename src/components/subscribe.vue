<template>

  <div class="container z-40 mx-auto md:justify-center bg-gray-50">
    <div class=" w-5/6 py-10 inline-block border bg-white ">
     <div class="md:grid md:grid-cols-2 md:items-center md:justify-between">
        <div class="pl-8">
        <h1 class="justify-self-start">Subscribe Now for Get Special Features! </h1>
        <p class="pt-4"> Let's subscribe with us and find the fun.</p>  
        </div>  
        <div class="pl-8 flex justify-start pt-8 md:pt-0">
       <button class="button ">Subscribe Now</button>
      </div>
    </div>
      </div>  
    </div>
  

       

</template>

<script>
export default {

  data () {
   
}
}

</script>


<style scoped lang="scss">

div h1{
  font-weight : 750 ;
  color : black ;
  font-family: 'Rubik', sans-serif;
  font-size: 30px;
  text-align: start;
 
}

div p{
  font-family: Verdana, sans-serif;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
  text-align: start;


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
  box-shadow: 1px 10px 25px -10px red ;
  cursor: pointer;
  outline: none;
  }

</style>
