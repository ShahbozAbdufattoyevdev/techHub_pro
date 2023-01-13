<template>
    <main class="site_main">
<h2 class="reason heads">Nima uchun aynan <span class="getstyle">TechHub</span></h2>
    <section class="main_first">
<div class="container">
    <div class="education">
<h2>Education</h2>
<p>Bizning darslar tajribali ustzlar tomonidan olib boriladi,</p>
    </div>

    <div class="aloritmlash">
<h2>Algoritmlash</h2>
<p>Bizning kursimizni boshqalardan farqi asosan bizda Algoritmlashga etibor beriladi</p>
    </div>

    <div class="practise">
<h1>Practics</h1>
<p>bizning kurslarimizni bitirgan har bir o'quvchi haqiyqiy realniy proektda ishlash imkoniyatiga ega boladi, va kurslarimizni alo darajada tugatgan o'quvchilar o'zimizning "TechHub" kompaniyasi tomonidan ish bilan taminlanadi</p>
    </div>
</div>
    </section>

<!-- first section end  -->

<!-- second section start  -->
    
<h2 class="heads">Ochiq darslar</h2>
<ul class="btn_list">
    <button>Html/Css</button>
    <button>Javascript</button>
    <button>React/Vue</button>
    <button>NodeJs</button>
    <button>Python</button>
</ul>
<section class="main_second">
<div class="container">
<div>
<h2>Rasm, videolink,</h2>
</div>
<div>
<h2>Rasm, videolink,</h2>
</div>
<div>
<h2>Rasm, videolink,</h2>
</div>
<div>
<h2>Rasm, videolink,</h2>
</div>
</div>
</section>
    </main>
    
</template>
<script>
export default {
    name: 'MainApp'
}
</script>




<style scoped>
.site_main{
    overflow:hidden;
}
.container{
    width: 1290px;
    margin: auto;
  
}
 .main_first{
   background-color:rgb(124, 124, 16) ;
    height: 500px;
    color: #232323;
 padding-left: -15px;
 }
.main_first .container{
    display: flex;
justify-content: space-between;
align-items: center;
padding-top:50px ;
}
.main_first .container div{
    width: 400px;
    height: 400px;
  transition: all 0.5s;
    border: 1px solid #232323;
}
.main_first .container div:hover{
      box-shadow: 0 0 15px #232323;
      transform: translate(7px, -7px);
}
.getstyle{
    background-color: #232323;
    color: yellow;
}
.heads{
    font-size: 40px;
    text-align: center;
    margin-top: 80px;
    margin-bottom: 80px;
}
.reason{
    position: relative;
    left: 50px;
}
.heads::before{
    content: '◉';
    font-size: 20px;
    position: relative;
    top: -5px;
    left: -5px;
}



/* main second  */

.main_second .container{
    width: 100%;
    height: 400px;
    background-color:rgb(124, 124, 16) ;
    display: flex;
    justify-content: space-evenly;
    padding-top: 80px;
}
.btn_list{
    display: flex;
    width: 1290px;
    gap: 50px;
    margin-right: auto;
    margin-left: auto;
}
.btn_list button{
    width: 120px;
    height: 30px;
    font-size: 15px;
    background-color: transparent;
    border-radius: 15px;
  
    border: 2px solid #232323;
}
.btn_list button:hover{
      box-shadow:inset 0 0 15px rgb(96, 230, 163);
    border: 2px solid  rgb(96, 230, 163);
}
.main_second .container div{
    width: 290px;
    height: 300px;
    background-color: antiquewhite;
}
</style>