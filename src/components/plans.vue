<template>

  <div class="container background ">
      <div class="row justify-content-center align-items-center container-2">
        <div class="col-md-5 col-sm-12 justify-content-center align-items-center">
        <h1 class="text-center">Choose Your Plan</h1>
        <p class="text-center">let's choose the package that is best for you and explore it happily and cheerfully.</p>
      </div>
  
      </div>
      <div class="row justify-content-center ">
    
      <div class="col-md-3 col-sm-12 border container-1 shadow">
        <div class="col-md-12 ">
            <img src="@/assets/Free.svg" class="image"alt="Random Name" >
            <h1 style="text-align: center;">Free plan</h1>
            <div class="col-md-12 justify-content-center">
             <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Unlimited Bandwidth
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Encrypted Connection
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> No Traffic Logs
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Works on All Devices
        </div>
      </div>
      </div>
       <div class="raw">
        <div class="end">
      <div class=" d-flex align-items-end plan justify-content-center">
        <h4>$12  <span> / mo</span></h4>
      </div>
       <button class="btn btn-outline-danger rounded-pill ml-8" type="submit"><span>Select</span></button>
     </div>
      </div>
       </div> 
      </div>
       
      
        <div class="col-md-3 col-sm-12 border container-1 shadow">
        <div class="col-md-12 ">
            <img src="@/assets/Free.svg" class="image"alt="Random Name" >
            <h1 style="text-align: center;">Standard plan</h1>
            <div class="col-md-12 justify-content-center">
             <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Unlimited Bandwidth
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Encrypted Connection
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Yes Traffic Logs
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Works on All Devices
        </div>
      </div>
      <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Connect anywhare
        </div>
      </div>
    </div>

       <div class="raw align-items-end">
        <div>
      <div class=" d-flex plan justify-content-center align-self-bottom">
        <h4>$12  <span> / mo</span></h4>
      </div>
       <button class="btn btn-outline-danger rounded-pill ml-8" type="submit"><span>Select</span></button>
     </div>
      </div>
      </div>
     
      </div>


        <div class="col-md-3 col-sm-12 border container-1 shadow">
        <div class="col-md-12 ">
            <img src="@/assets/Free.svg" class="image"alt="Random Name" >
            <h1 style="text-align: center;">Premium plan</h1>
            <div class="col-md-12 justify-content-center">
             <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Unlimited Bandwidth
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Encrypted Connection
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Yes Traffic Logs
        </div>
      </div>
        <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Works on All Devices
        </div>
      </div>
       <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Connect anywhare
        </div>
      </div>
       <div class="d-flex align-items-center">
        <img src="@/assets/jam_check.png">
       <div class="align-self-center list-data"> Get New Features
        </div>
      </div>

      <div class="align-self-bottom">
      <div class="d-flex plan justify-content-center align-items-center ">
        <h4>$12  <span> / mo</span></h4>
      </div>
       <button class="btn btn-outline-danger rounded-pill ml-8" type="submit"><span>Select</span></button>
      </div>
       </div> 
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
.shadow{
  box-shadow: 10px;
}
background{
  background-color: red !important;
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
  margin-top: 50px;
  margin-bottom: 25px;
  font-weight : 800 ;
  color : black ;
  font-family: 'Rubik', sans-serif;
  font-size:25px;
  text-align: start;
}

div p{
  font-family: Verdana, sans-serif;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
}
.end{
  flex-direction: column;

  
}
.container-1{
  padding:20px ;
  border:solid 0.5px grey;
  box-radius:10px !important;
  margin: 20px;
}
.container-1:hover {
  border:solid 1.5px red !important ;
}
.container-2{
  margin-bottom: 30px ;
  margin-top: 30px ;
 
}
.list-data{
  margin:10px ;
  font-family: Verdana, sans-serif;
  text-align: start;
  color: rgba(0,0,0,.5);
  font-weight : bold ;
  font-size: 11px;
}
.plan{
  margin-top: 30px;
}
.rounded-pill{
  padding : 5px 50px 5px 50px !important;
}


</style>
