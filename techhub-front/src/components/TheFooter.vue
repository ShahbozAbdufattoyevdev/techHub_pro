<template>
    <footer class="site_footer">
        <div class="container">
            <ul class="lists">
            </ul>
            <ul class="lists"></ul>
            <ul class="lists">
                <h3>Sahifalarimiz</h3>
                <img src="../assets/facebook.svg" alt="">
                <img src="../assets/telegram.svg" alt="">
                <img style="width:25px" src="../assets/instagram-icon.svg" alt="">

            </ul>
            <ul class="lists">
                <img class="logo" src="../assets/Logo.jpg" alt="">

            </ul>
            <p class=""> TechHUb &copy; 2023 - All Programmers, TechHub team.</p>
        </div>
    </footer>
</template>


<script>
export default {
    name: 'TheFooter'
}
</script>




<style scoped>
.site_footer {
    height: 400px;
    background-color: #FEDD5B;
    margin-top: 100px;
}

.container {
    display: flex;
    justify-content: space-around;
}

.logo {
    width: 150px;
    height: 150px;
}

.lists {
    width: 400px;
    height: 400px;
    border: #FEDD9B 2px solid;
}
</style>