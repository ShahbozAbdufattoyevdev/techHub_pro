<template>
    
     <header class="site_header">
<div class="container">
    <div class="nav_bar">
<h1>TechHub <span class="logo"><img src="" alt="" ></span></h1>
<input class="search" name="search" type="search" placeholder="Search our lessons">
<ul class="lists">
    <li><a href="#">About</a></li>
    <li><a href="#">Goals</a></li>
</ul>
<button>Contact</button>
</div>

<div class="header_style">
<div>
<h1>Coding simple with us</h1>
<h2>TechHub jamoasi sizni o'z kurslariga taklif qiladi</h2>
<ul class="btn_list">
    <button>Yozilish</button>
<button>Demo lesson</button>
</ul>
</div>

</div>
</div>
    </header>


    <!-- header end  -->

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
*{
    list-style: none;
}
.container{
    width: 1290px;
    margin: auto;
}
.site_header{
    height: 700px;
    line-height: 50px;
}
button{
    width: 160px;
    height: 35px;
    border-radius: 25px;
    background-color: rgb(96, 230, 163);
    color: #232322;
   border: transparent;
    font-size: 20px;
    display: flex;
    align-items: center;
    justify-content: center;
}
button:hover{
    background-color: yellow;
    transition: all 0.5s;
    color: #232322;
    border:ridge #232322 2px;
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
    z-index: 111;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: rgb(124, 124, 16);
 position: fixed;
}

.lists{
    width: 200px;
    display: flex;
    justify-content: space-between;
    list-style: none;
 
    font-size: 20px;
 
}
.btn_list{ 
    display: flex;
}
.btn_list button{
    width: 180px;
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
 position: relative;
 top: 200px;
}
.search{
    width: 300px;
    height: 35px;
    border-radius: 20px;
    outline: none;
   border: none;
   background-color: rgb(96, 230, 163); 
}
.search::placeholder{
    color: #232323;
    font-size: 15px;
    padding-left: 10px;
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