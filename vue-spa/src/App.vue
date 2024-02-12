<template>
  <div id="app">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
 <body>  
 <title>Free Book Me In Scotty</title>
  <header>
       <nav class="navbar navbar-expand-sm fixed top  ">
        <div class="container">
  <a class="navbar-brand" href="#" style="color: white;">
    <i class="fas fa-calendar fa-2x"></i> Book Me In Scotty
    <p>Host & Share Events!</p>
</a>

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#" style="color:white;"><i class="fas  fa-fingerprint"></i> Login <span class="sr-only">(current)</span></a>
      </li>
       <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" style="color:white;" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          <i class="fas fa-globe"></i> English
        </a>
         <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
    </li>
       
   <li class="nav-item">
       <button type="button" class="btn btn-danger btn-lg"><i class="fas fa-calendar-day"></i> Browse Events</button>
      </li>
     
       <li class="nav-item">
    <button type="button" class="btn btn-light">
    <i class="fa-solid fa-mobile fa-1x"></i>
</button>
      </li>
    </ul>
  </div>
  </div>
</nav>
    </header>
    <main>
<div id="main-image" class="jumbotron">
    <div class="container">
        <div class="row">
            <div class="col-sm-6 btn-holder ">
            </div>
            <div class="col-sm-6">
                <h1 class="text-left" style="color: orange; font-weight: bold;">Book Me In Scotty</h1>
                <h1 class="text-left" style="color: white; font-weight: bold;">Organize, Host and Share your Events</h1>
                <br>

                <a href="#" class="btn btn-light btn-lg active" role="button" aria-pressed="true">
                    <i class="fas fa-cloud-download-alt"></i> For Individuals
                </a>

                <a href="#" class="btn btn-success btn-lg active" role="button" aria-pressed="true">
                    <i class="fas fa-shopping-cart"></i> For Business
                </a>

                <a href="#" class="btn btn-light btn-lg active" role="button" aria-pressed="true">
                    <i class="fas fa-book"></i> Docs
                </a>
               </div>
               </div>
              </div>
              </div> 



    </main>
</body>
</html>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style>

 .nav-item {
          margin-right: 10px; /* Adjust the value according to your preference */
            }

header {
     background-size: cover;
}

</style>
