<template>

  <div class="home">
  
 <nav class="navbar navbar-expand-lg ">

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse d-flex justify-content-center" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Pricing</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
  </div>
</nav>

<div>
<center>
<div class="maintitle">
<h3 class="">- REVOLUTION -</h3>
<h1 class="barberShop">Barber Shop</h1>
<p>SEIT 1950 IN DUSSELDORF</p>
_________________________________

</div>
</center>
<img class="imgmain" src="../assets/barber-shop-san-diego-ca-scaled.jpg" alt="">

</div>

<div id="cards">
<div class="row">
<div class="col-md-3">
<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/istockphoto-516230773-612x612.jpg" alt="Card image cap">
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
</div>
<div class="col-md-3">
 <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/barber-shop-san-diego-ca-scaled.jpg" alt="Card image cap">
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
</div>
<div class="col-md-3">
 <div class="card" style="width: 18rem;">
  <img class="card-img-top" src="../assets/barbershop-barbershop-interior-bw-b-w-black-white-117722218.jpg" alt="Card image cap">
  <div class="card-body">
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
  </div>
</div>
</div>
</div>
</div>

<div class="maininfo">

<div class="photo"></div>
<div class="info">
<h2>Lorem ipsum dolor sit amet</h2>
<blockquote >Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta reiciendis esse explicabo beatae culpa porro minus sunt tempore. Saepe totam deleniti ab dolorem, impedit reiciendis ex soluta asperiores illum officia!
Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odit error expedita iure non itaque neque dignissimos aliquam eveniet repudiandae repellendus ex velit corrupti maxime perferendis consectetur illo nam quam vero quis, corporis maiores aspernatur assumenda praesentium asperiores, impedit optio saepe odit!</blockquote>
<button class="btn">Button</button>
</div>
</div>

<div class="location">
<div class="locationphoto"></div>
<div class="locationinfo">
<h2>Lorem ipsum dolor sit amet</h2>
<h6>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque, aspernatur obcaecati voluptate et optio sit! Quasi reprehenderit perspiciatis sunt temporibus fugiat cum, aspernatur pariatur laudantium corrupti delectus asperiores ab iure.</h6>
<h2>Lorem ipsum dolor sit</h2>
<h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eveniet iste architecto dolorum numquam veritatis est dolores amet voluptatibus? Aut, facere totam at iste assumenda veritatis officiis sunt quis nostrum vero!</h5>
</div>
</div>

  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style >
.navbar{
  background-color: black;
}
.maintitle{
  position:absolute;
  z-index: 1;
  color:rgb(228, 218, 218);
  margin-top: 250px;
  margin-left: 610px;
 
}
.barberShop{
  font-weight: 800;
}
.nav-link{
  color: aliceblue;
}
#header{
  background-image: url('../assets/barber-shop-san-diego-ca-scaled.jpg');
}
.imgmain{
  height: 100vh;
  width: 100%;
  background-size:cover;
  background-position: center;
  opacity: 0.10;
}
.card-group{
width: 300px;
height: 400px;
}
.card-body{
  background-color: black;

}
.card{
  border: none;
  margin-left: 230px;
  margin-top: 80px;
}
.card-text{
  color: white;
}
body{
  background-color: black;
}
.maininfo{
  width: 100%;
  height: 550px;
  display: flex;
  background-color:rgb(8, 7, 7);
}
.info{
  padding-top: 70px;
  width: 500px;
  height: 400px;
  margin-left: 80px;
  margin-top:10px;
  
}
.photo{
  width: 500px;
  height: 400px;
  margin-left:230px;
  margin-top: 70px;
  background-image: url('../assets/istockphoto-516230773-612x612.jpg');
}
h2{
  color: rgb(212, 201, 201);
  margin-right: 100px;
}

.btn{
  background-color: rgb(157, 109, 63);
  width: 150px;
  margin-right: 320px;
  margin-top: 40px;
}
.location{
  width: 100%;
  height: 600px;
  background-image: url('../assets/city.jpg');
  background-size: 100% ;
  opacity: 0.10;
  display: flex;
}
.locationphoto{
  width: 500px;
  height: 400px;
  margin-left:230px;
  margin-top: 70px;
  background-image: url('../assets/interesting-areas-google.png');
  
}
.locationinfo{
  width: 500px;
  height: 400px;
  margin-left:100px;
  margin-top: 70px;
}


</style>