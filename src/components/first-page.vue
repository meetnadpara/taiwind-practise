<template>

  <div class="container">
    <div class="row align-items-center justify-content-center">
      <div class="col-md-6 col-sm-12 container-1">
       
        <h1>Want anyting to be easy with <span>LaserVPN.</span></h1>
        <p>Provide a network for all your needs with ease and fun using <span>LaserVPN</span> discover interesting features from us.</p>  
        <div class="get-started"><button class="button">Get Started</button></div>
      
    </div>
    
      <div class="col-md-6 col-sm-12">
       
        <img src="@/assets/Illustration1.svg" class="img-fluid">
      
    </div>
  
  <div class="col-md-12 col-sm-12 container-2 shadow">
  
    <div class="raw d-flex box-shadow align-items-center">
      
      <div class="col-md-4 col-sm-12 vl d-flex justify-content-center">
        <div class="raw d-flex box-shadow align-items-center">
        <div class="col align-self-center">
          <img src="@/assets/user.svg" class="img-fluid">
        </div>

        <div class="col d-block align-self-center">
          <div class="raw align-self-center">
          <h3>90+</h3>
        </div>
        <div class="raw align-self-center">
         <p>Users</p>
        </div>
        </div>
         </div>
       </div> 
     
      <div class="col-md-4  col-sm-12 vl d-flex justify-content-center">
        <div class="raw d-flex box-shadow align-items-center">
        <div class="col align-self-center">
          <img src="@/assets/user.svg" class="img-fluid">
        </div>

        <div class="col">
          <div class="raw">
          <h3 class="border">30+</h3>
        </div>
        <div class="raw">
         <p class="border">Location</p>
        </div>
        </div>
         </div>
       </div> 
        <div class="col-md-4  col-sm-12  d-flex justify-content-center">
        <div class="raw d-flex box-shadow align-items-center">
        <div class="col align-self-center">
          <img src="@/assets/Server.svg"class="img-fluid" >
        </div>

        <div class="col align-self-center">
          <div class="raw">
          <h3>50+</h3>
        </div>
        <div class="raw">
         <p>Server</p>
        </div>
        </div>
         </div>
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
      user:{
        name:'Users' ,
        quantity: 90 ,
        image: "@/assets/user.svg"
           },
       location:{
        name:'Locations' ,
        quantity: 30 ,
        image: '@/assets/user.svg'
           },
       server:{
        name:'Servers' ,
        quantity: 50 ,
        image: '@/assets/Server.svg'
           }

}
}
}

</script>


<style scoped lang="scss">

div h1{
  margin-top: 25px;
  margin-bottom: 25px;
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
.vl {
  border-right: 1px solid #DED5D5;
  margin-left: -3px;
  border-opacity: 0.1 !important;
 
}

.get-started{
  text-align: start;
  margin-top: 35px;
  }
.container-1{
  margin-bottom: 20px ;
}
.container-2{
  margin-bottom: 20px ;
  margin-top: 100px ;
  padding: 20px;
}
</style>
