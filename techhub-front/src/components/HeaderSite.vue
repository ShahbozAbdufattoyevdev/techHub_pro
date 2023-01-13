<template>
    
     <header class="site_header">
<div class="container">
    <div class="nav_bar">
<h1>TechHub <span class="logo"><img src="assets/" alt=""></span></h1>
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

</div>
</div>
    </header>


    <!-- header end  -->

    <!-- main start -->

   
   
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
}
.site_header{
    
    height: 700px;
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