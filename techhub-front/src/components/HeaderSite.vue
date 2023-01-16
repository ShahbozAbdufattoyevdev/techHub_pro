<template>

    <header>
        <div class="header_under"></div>
        <div class="header">
            <div class="container">
                <div class="nav_bar">
                    <div class="logo">
                        <a class="logo__item" href="#">
                            Tech<span>Hub</span>
                        </a>
                    </div>
                    <div class="search">
                        <label for="search"> <i class="fa-solid fa-magnifying-glass"></i></label>
                        <input placeholder="Search..." type="search" name="search" id="search">
                    </div>
                    <ul class="nav">
                        <li><a href="#">About</a></li>
                        <li><a href="#">Goals</a></li>
                    </ul>
                    <a class="contact" href="tel:+">Contact</a>
                </div>
            </div>
        </div>


        <div class="banner">
            <div class="container">
                <h1 class="banner__h1">Coding simple with us</h1>
                <h2 class="banner__h2">TechHub jamoasi sizni o'z kurslariga taklif qiladi</h2>
                <ul class="btn__list">
                    <li><a href="#">Yozilish</a></li>
                    <li><a href="#">Demo lesson</a></li>
                </ul>
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
header {
    width: 100%;
}

.header {
    width: 100%;
    background-color: #FEDD5B;
    padding: 10px 0px;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 100;
    border-bottom: 1px solid black;
}

.header_under {
    width: 100%;
    height: 55px;
}

.nav_bar {
    width: 100%;
    align-items: center;
    display: flex;
    justify-content: space-between;
}

.logo__item {
    font-weight: 600;
    font-size: 28px;
    color: black;
    line-height: 30px;
}

.logo__item span {
    color: #1b440c;
}

.nav {
    display: flex;
    gap: 50px;
    font-size: 20px;
}

.nav a {
    color: black;
}

.nav a:hover {
    transition: .3s;
    color: #60604f;
}

#search {
    padding: 8px 0px 8px 32px;
}

.search label {
    position: absolute;
    left: 8px;
    top: 9px;
    font-size: 14px;
}

.search {
    width: 300px;
    position: relative;
}

.search input {
    width: 50%;
    transition-duration: .5s;
    border-radius: 6px;
    outline: none;
    border: .5px solid transparent;
    background-color: rgb(174, 255, 215);
}

.search input:focus {
    border: .5px solid #1b440c;
    transition: .5s;
    width: 100%;
    background-color: rgb(224, 255, 240);
}

.contact {
    width: 150px;
    padding: 8px 10px;
    border-radius: 15px;
    background-color: rgb(96, 230, 163);
    color: #232322;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8px;
    font-weight: 500;
    transition-duration: .3s;
}

.contact span {
    font-size: 18px;
}

.contact i {
    opacity: 0;
    display: none;
}

.contact:hover i {
    display: block;
    opacity: 1;
}

.contact:hover {
    transition: .3s;
    background-color: rgb(134, 242, 188);
    transition: all 0.5s;
}

.banner {
    height: 80vh;
    display: flex;
    align-items: center;
    background: url(../assets/banner1.jpg);
}

.banner .container {
    width: 100%;
    max-width: 700px;
    padding: 30px 25px 50px;
    background: rgba(0, 0, 0, 0.5);
    border-radius: 25px;
}

.banner__h1 {
    text-transform: uppercase;
    text-align: center;
    font-size: 40px;
    color: #a78500;
}

.banner__h2 {
    margin-top: 20px;
    color: white;
}

.btn__list{
    display: flex;
    margin-top: 20px;
    gap: 20px;
}

.btn__list li{
    display: inline-block;
    /* background: ; */
}


/* .site_main {
    width: 1350px;

}

.main_first {
    background-color: #60604f;
    margin-top: 100px;
    width: 100%;
    display: flex;
    justify-content: space-between;
}

.main_first div {
    width: 500px;
    height: 100vh;
    box-shadow: 0 0 15px rgb(124, 124, 16);
} */
</style>