<template>
    
     <header class="site_header">
<div class="container">
    <div class="nav_bar">
<h1>TechHub <div class="logo"></div></h1>
<li class="search"><input class="search" name="search" type="search" placeholder="Search our lessons"><span><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" style="fill: rgba(0, 0, 0, 1);transform: ;msFilter:;"><path d="M10 18a7.952 7.952 0 0 0 4.897-1.688l4.396 4.396 1.414-1.414-4.396-4.396A7.952 7.952 0 0 0 18 10c0-4.411-3.589-8-8-8s-8 3.589-8 8 3.589 8 8 8zm0-14c3.309 0 6 2.691 6 6s-2.691 6-6 6-6-2.691-6-6 2.691-6 6-6z"></path><path d="M11.412 8.586c.379.38.588.882.588 1.414h2a3.977 3.977 0 0 0-1.174-2.828c-1.514-1.512-4.139-1.512-5.652 0l1.412 1.416c.76-.758 2.07-.756 2.826-.002z"></path></svg></span></li>
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

*{
    list-style: none;
    line-height: 50px;
}
.container{
    width: 1290px;
    margin: auto;
}
.site_header{
    height: 700px;
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
.search{
    display: flex;
}
.nav_bar{
    width: 1290px;
    height:80px;
    margin-right: auto;
    margin-left: auto;
    z-index: 111;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #FEDD5B;
 position: fixed;
}
.nav_bar h1{
gap: 10px;
    display: flex;
    align-items: center;
}
.logo{
    width: 80px;
    height: 80px;
    border-radius: 50%;
   background-image: url(../assets/Logo.jpg);
   background-size: cover;
   background-repeat: no-repeat;
   background-position: center;
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
    text-decoration: underline rgb(96, 230, 163);
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
    border-radius:3px;
    outline: none;
   border: none;
   background-color: rgb(96, 230, 163); 
   font-size: 15px;
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