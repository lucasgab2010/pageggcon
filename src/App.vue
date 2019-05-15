<template>
<header class="container">
  <div class="col-sm-12 sm-6">
  <div id="app">
    <img src="./assets/logo.png" class="logo">
    <router-view/>
  </div>
  </div>

    <div class="row">
      <div class="col-sm-6">
          <img src="./assets/images.jpg" alt="imagen" class="img-fluid " >
      </div>

      <div class="col-sm-6 text-center">
       <p class="p">tu proyecto web y tu proyecto de obra...</p>
       <form action="">
                  <input type="text" class="form-control rounded-0 my-4 text-center"
                   placeholder="escribe tu email">
                  <button class="btn btn-light btn-outline rounded-0">
                    SUSCRIBIR
                  </button>
        </form>
      </div>
   </div>
</header>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top:60px;

  
}
.p{
   color: #fff;
   font-family: sans-serif;
}
body, html{
height: 100%;
padding: 0;
margin: 0;
}

.logo{
  margin-top: 20px;
  padding: 1px;
  height: 200px;
}

.form-control{
  background: transparent !important;
  color: #fff !important;
}

body{
  margin: 0;
background: linear-gradient(rgba(95,114,190,.9),rgba(155,35,234,.7)), url("./assets/img1.jpg");
background-size: cover;

}
</style>
