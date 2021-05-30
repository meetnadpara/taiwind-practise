<template>
  <div class="container">

    <nav class="navbar navbar-expand-lg navbar-light">
  <div class="navbar-brand">  
  <img src="@/assets/logo.svg" class="image-logo"> 
  </div>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span> 
  </button>


  <div class="collapse navbar-collapse "  id="navbarSupportedContent" >

    <ul class="navbar-nav mr-auto font-weight-bold">
      <li class="nav-item">
        <a class="nav-link" href="#">About <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Feature</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>

      <li class="nav-item">
        <a class="nav-link" href="#">Testimonials</a>
      </li>

      <li class="nav-item">
        <a class="nav-link" href="#">Help</a>
      </li>
    </ul>
  </div>
   <div class="collapse navbar-collapse nav-right flex-row-reverse"  id="navbarSupportedContent" >
    <!-- <div class="collapse navbar-collapse navbar-nav mr-auto">   -->
      
      <button class="btn btn-outline-danger rounded-pill ml-3" type="submit"><span>Sign Up</span></button>
  <p class="nav-item font-weight-bold">Sign In</p>
  </div>
  
</nav>
  </div>
</template>

<script>
export default {
 
}
</script>


<style scoped lang="scss">
.navbar{
  width : 100% ;
  padding : 15px !important;
  display : flex !important;
}

.nav-item{
  font-size : 15px !important;
  margin : 8px ;
}

.navbar-nav{
  justify-content : center ;
}

.rounded-pill{
  padding : 5px 30px 5px 30px !important;
}

nav div p{
  font-family: Verdana, sans-serif;
}
.image-logo{
  margin-right: 60  px;
}
</style>
