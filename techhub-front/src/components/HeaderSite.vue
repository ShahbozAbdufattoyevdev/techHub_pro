<template>
   <div class="container">
     <header class="site_header">
<div class="nav_bar">
<h1>TechHub <span class="logo"></span></h1>
<ul class="lists">
    <li><a href="#">About</a></li>
    <li><a href="#">Goals</a></li>

</ul>
<button>Contact</button>
</div>

<div class="header_style">
<div>
<h1>Lorem ipsum dolor sit amet.</h1>
Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ratione, magni.
</div>

<div>

</div>
</div>
    </header>


    <!-- header end  -->

    <!-- main start -->

    <main class="site_main"> 
<section class="main_first">
    <div class="frontend">

    </div>
    <div class="beckend">

    </div>
</section>
    </main>

   </div>
</template>
<script>
export default {
    name: "HeaderSite"
}
</script>




<style scoped>
body{
    background-color: yellow;
    color: #232322;
   
}
.container{
    width: 1290px;
    margin: auto;
    border: dotted 2px red;
}
.site_header{
    width: 1350px;
    height: 500px;
}
button{
    width: 140px;
    height: 35px;
    border-radius: 25px;
    background-color: rgb(96, 230, 163);
    color: #232322;
    border: none;
    font-size: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}
button:hover{
    background-color: yellow;
    transition: all 0.5s;
    color: #232322;
}
button:hover::after{
    content: "→";
    font-size: 20px;
    position: relative;
    left: 10px;
    color: #232322;
}

.nav_bar{
    width: 1290px;
    margin-right: auto;
    margin-left: auto;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: rgb(124, 124, 16);
 position: fixed;
}
.logo{
    width: 50px;
    height:50px;
    border-radius: 50%;
    background-image: url();
}
.lists{
    width: 200px;
    display: flex;
    justify-content: space-between;
    list-style: none;
 
    font-size: 20px;
    position: relative;
    left: 200px;
}
.lists li a{
 text-decoration: none;
 color: #232322;
}
.lists li a:hover{
    color: aquamarine;
    text-decoration: #232323;
}
.header_style{
    width: 100%;
    display: flex;
 justify-content: space-between;
}

.header_style div:nth-child(1){
    width: 400px;
    height: 400px;
    border-radius: 100%;
    background: radial-gradient(aqua, yellow, #232323 );
}







.site_main{
    width: 1350px;
  
}
.main_first{
    background-color: #60604f;
    margin-top: 100px;
    width: 100%;
display: flex;
justify-content: space-between;
}
.main_first div{
    width: 500px;
    height: 100vh;
    box-shadow: 0 0 15px rgb(124, 124, 16);
}
</style>