<script setup>
</script>

<template>
  
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style.css" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <title>Forget Store</title>
</head>

<body>
  <header>
    <div class="col-12">
      <nav class="container-fluid nav-forget">
        <div class="menu">
          <div class="brand">
            <img src="../components/img/logo1.png" alt="" srcset="" />
        </div>
        <div class="menuarea">
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">About</a></li>
          </ul>
          <div class="menulogin">
            <button>Entrar</button>
          </div>
        </div>
      </div>
    </nav>
    <div class="categorias">
      <ul>
        <li>Ofertas</li>
        <li>Camisetas</li>
        <li>Moletom</li>
        <li>Bonés</li>
      </ul>
    </div>
    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="../components/img/prin1.png" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="../components/img/prin2.png" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="../components/img/prin3.png" class="d-block w-100" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    </div>
  </header>
  <div class="catalogogeral">
    <img src="../components/img/camisa/Retângulo-Arredondado-1.png" style="opacity: 60%; ">
  </div>
  <div class="modelos">
    <img src="../components/img/camisa/forget.png">
    <img src="../components/img/camisa/forget1.png">
    <img src="../components/img/camisa/forget.png">
    <img src="../components/img/camisa/forget1.png">
  </div>

</body>
</template>
<style>
* {
    margin: 0 auto;
    font-family:Arial, Helvetica, sans-serif;
    text-decoration: none;
}



.nav-forget {
    background-color: rgb(0, 0, 0);
    height: 60px;
}

.menu {
    padding: 0 1%;
}

.brand {
    float: left;
    margin-top: 2px;
}

.brand img {
    height: 35px;
    margin-left: 180px;
    padding: 10px;
}

.menuarea {
    float: right;
    display: flex;
    text-decoration: none;
}

.menuarea ul {
    display: flex;
    margin: 0 150px;
    position: relative;
    margin-top: 5px;
    text-decoration: none;
}

.menuarea ul a{
    color: rgb(255, 255, 255);
    text-decoration: none;
    margin: 0 55px;
    height: 30px;
    margin-top: 15px;
    display: flex;
    position: relative;
    text-decoration: none;
}



a:after{
    content: "";
    position: absolute;
    background-color: red;
    height: 5px;
    width: 0;
    left: -22px;
    bottom: -10px;
    transition: 0.3s;
}

a:hover:after {
    width: 200%;
    
}

.menulogin button{
    border-radius: 15px;
    margin-top: 10px;
    margin-right: 40px;
    padding: 8px;
    width: 100px;
    background-color: transparent;
    border-color: red;
    color: rgb(255, 0, 0);
}
.menulogin button:hover{
    color: #fff;
    background-color: red;
}

.categorias{
    max-width: 100%;
    display: block;
    margin: 0 auto;
    background-color: rgb(40, 40, 40);
    height: 30px;
}

.categorias ul{
    color: rgb(0, 0, 0);
    margin-left: 900px;


}

.categorias ul li{
    color: rgb(255, 0, 0);
    text-align: center;
    margin-top: 6px;
    margin-left: 30px;
    font-size: 15px;
    text-decoration: none;
    list-style-type: none;
    display: inline-flex;
}

.imgprin{
    width: 100vw;
}

.catalogogeral img{
    position: relative;
    left: 450px;
    top: 30px;
}

.modelos img{
    position: relative;
    top: 30px;
    left: 80px;
    margin: 25px;
    max-width:450px;
    max-height:300px;
    width: auto;
    height: auto;
    border: 1px solid rgba(0, 0, 0, 0.432);
    border-radius: 15px;
}




</style>
