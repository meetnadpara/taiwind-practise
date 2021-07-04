<template>

  <div class="container mx-auto bg-gray-50">
      <div class="justify-center pt-12 ">
       
        <h1 class="py-8 ">Choose Your Plan</h1>
        <p class="pb-12 px-30">let's choose the package that is best for you and explore it happily and cheerfully.</p>
      </div>


      <div class="grid md:grid-cols-3 gap-2 justify-center">  

      
        <div class=" mx-8 grid border rounded-lg bg-white hover:border-red-600 shadow">
         <div> 
          <div class=" justify-self-center pt-12">
            <img src="@/assets/Free.svg" class="justify-self-center object-scale-down">     
            <h1 class="my-8">Free plan</h1>  
         </div>     
        

        <div class="px-16 self-start">

        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Unlimited Bandwidth
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Encrypted Connection
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> No Traffic Logs
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Works on all devices
          </p>
        </div>  
    </div>
  </div>
      <div class="my-8 self-end">
        <h4 class="mb-5">Free</h4>
       <button class="button rounded-pill" type="submit"><span>Select</span></button>
     </div>   
      </div>

<div class="grid border mx-8 rounded-lg bg-white hover:border-red-600 shadow">
  <div>
          <div class=" justify-self-center pt-12">
            <img src="@/assets/Free.svg" class="justify-self-center object-scale-down"> 
            <h1 class="my-8">Standard Plan</h1>      
         </div>     
        

        <div class="px-16 self-start">

        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Unlimited Bandwidth
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Encrypted Connection
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Yes Traffic Logs
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Works on all devices
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Connect Anyware
          </p>
        </div>
       </div>
    </div>
      <div class="my-8 self-end">
        <h4 class="mb-5">$9  <span> / mo</span></h4>
       <button class="button rounded-pill" type="submit"><span>Select</span></button>
     </div>   
      </div>

      <div class="grid border mx-8 hover:border-red-600 bg-white rounded-lg shadow">
        <div>
          <div class=" justify-self-center pt-12">
            <img src="@/assets/Free.svg" class="justify-self-center object-scale-down">       
         </div>     
        <h1 class="my-8">Premium Plan</h1>

        <div class="self-start px-14">

        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Unlimited Bandwidth
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Encrypted Connection
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Yes Traffic Logs
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Works on all devices
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Connect Anyware
          </p>
        </div>
        <div class="flex mb-5 items-center">
          <img src="@/assets/greencheck.svg">
          <p class="ml-5 list-data"> Get New Features
          </p>
        </div>
       </div>
    </div>
      <div class="my-8 self-end">
        <h4 class="mb-5">$12  <span> / mo</span></h4>
       <button class="button rounded-pill" type="submit"><span>Select</span></button>
     </div>   
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
  width: 160px;
  height: 40px;
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
  box-shadow: 1px 10px 25px -10px red ;
  }

div h4{
  font-weight : 700 ;
  color : black ;
  font-size: 25px;
}
h4 span{
  font-family: Verdana, sans-serif;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 18px;
}
div h1{

  font-weight : 800 ;
  color : black ;
  font-family: 'Rubik', sans-serif;
  font-size:22px;

}
img{
  display: inline-block !important;
}

div p{
  font-family: Verdana, sans-serif;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
}

.list-data{

  font-family: Verdana, sans-serif;
  text-align: start;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
}

.rounded-pill{
  padding : 5px 50px 5px 50px !important;
}


</style>
