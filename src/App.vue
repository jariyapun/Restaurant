<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <section>
  <header>
    <nav class="navbar  fixed-top" style="background-color: #134B8A;">
  <div class="container-fluid">
    <a class="navbar-brand"></a>
    <form class="row g-3">
      <div class="col-auto">
    <a class="navbar-brand " href="#" >
        <img src="https://cdn-icons-png.flaticon.com/128/6083/6083760.png"  width="45" height="30" class="d-inline-block align-text-top" > <span class="position-absolute  bottom-50 start-100 translate-middle badge border border-light rounded-circle bg-danger p-1 "><span class="visually-hidden">unread messages</span></span> 
    </a>
  </div>
  <div class="col-auto">
    <a class="navbar-brand  " href="#" >
      <img src="https://cdn-icons-png.flaticon.com/128/3135/3135789.png"  width="45" height="35" class="d-inline-block align-text-top">
    </a>
  </div>
  <form class="col-auto mt-4  " >
      <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false" style="color:white;" >
            AKKarapool
          </a>
          <ul class="dropdown-menu" >
            <li><a class="dropdown-item" href="#" >Logout</a></li>
          </ul>
        </form>
 </form>
  </div>
</nav>
  </header>

  <div style="margin-top: 70px;" class="container-fluid fixed-top">
    <div class="container-xl">
      <form class="row g-3">
        
        <div class="col-5 ">
          <div style="margin-top: 90px; margin-right: 10px;" class="container-fluid fixed-top">
  <div class="container ">
     <h3 class="font-kanit">Place List </h3>
    </div>
</div>

<div style="margin-top: 86px; margin-left: 740px;" class="container-fluid fixed-top">
  <div class="container-sm">
     <h2 style="color: #134B8A;" >| </h2>
    </div>
</div>
  
<div style="margin-top: 90px; margin-left: 870px;" class="container-fluid fixed-top">
<div class="col-3 ">
    <form class="form-inline active-cyan-3 active-cyan-4">
            <input class="form-control rounded-pill border-primary" type="text" placeholder="Search name..." aria-label="Search">
          </form>
          
  </div>
</div>

  <div class="container-fluid fixed-top" style="margin-top: 90px; margin-left:620px;">
    <div class=" dropdown " >
  <button class="btn dropdown-toggle rounded-pill border-primary col-md-2" type="button" data-bs-toggle="dropdown" aria-expanded="false">
    restaurant
  </button>
  <ul class="dropdown-menu">
    <li><a class="dropdown-item" href="#">restaurant</a></li>
    <li><a class="dropdown-item" href="#">Bakery</a></li>
    <li><a class="dropdown-item" href="#">Cafe</a></li>
  </ul>
</div>
  </div>
          </div>
        </form>
        <TheWelcome></TheWelcome>
      </div>
      
      </div>
      
</section>
 
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
