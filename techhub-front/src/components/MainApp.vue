<template>
    <main class="site_main">
<h2 class="reason heads">Nima uchun aynan <span class="getstyle">TechHub</span></h2>
    <section class="main_first">
<div class="container">
    <div>

    </div>

    <div>

    </div>

    <div>

    </div>
</div>
    </section>
<div class="container">



</div>
    </main>
    
</template>
<script>
export default {
    name: 'MainApp'
}
</script>




<style scoped>
.container{
    width: 1290px;
    margin: auto;
}
 .main_first{
    background-color: #232323;
    height: 500px;
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
    border: 1px solid yellow;
}
.main_first ,.container div:hover{
      box-shadow: 0 0 15px yellow;
      transform: translate(10px, -10px);
}
.getstyle{
    background-color: #232323;
    color: yellow;
}
.heads{
    font-size: 30px;
    text-align: center;
}
.reason{
    position: relative;
    left: 50px;
}
.reason::before{
    content: '◉';
    font-size: 20px;
    position: relative;
    top: -3px;
    left: -5px;
}
.main_first div:nth-child(1){
 color: yellow;
}
</style>