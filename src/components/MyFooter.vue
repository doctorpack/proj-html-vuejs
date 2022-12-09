<template>
    <div class="footer-background">
        <div class="footer-container">
            <div>
                <img class="logo-footer" src="../assets/img/logo_footer.png" alt="">
            </div>
            <div class="footer-nav-backgorund">
           
                <div class="footer-nav">
                    <div v-for="element in footerNavbarOptions" :key="element" v-html="element"></div>
                </div>
            </div>
        </div>
        <div class="social-credits-container">
            <div class="credits">
                <p>Copyright 2012-2020 | AVADA THEME BY THEMEFUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS</p>
            </div>
            <div class="socials">
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-youtube"></i></a>
            </div>
        </div>
       
    </div>
    
</template>

<script>
    export default {
        props:{
            footerNavbarOptions: Array,
        }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/common.scss";
    // COMMON
    a{
        color: white;
    }
    // FOOTER
    .footer-background{
        background-color: #272b34;
    }
    .footer-container{
        width: 100%;
    margin: 0 auto;
    display: flex;
   
    align-items: center;
    justify-content: space-between;
    }
    .logo-footer{
        height: 30px;
        margin-left: 30px;
    }
   
    .footer-nav-background{
        background-color: #272b34;
        height: 70px;
        width: 100%;
        display: flex;
        align-items: center;

    }
    .footer-nav {
        height: 100px;
        width: 100%;
        display: flex;
        font-weight: bold;
        font-size: 80%;
        align-items: center;
        justify-content: flex-end;
        color: #6b6b6c;
    }
    // LOWER FOOTER
    .lower-footer-container{
        width: 30%;
        margin: 0 auto;
        text-align: center;
        color: white;
        padding-top: 100px;
    }
    .social-credits-container{
        background-color: #1e2129;
        height: 100px;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .credits{
        color: #6b6b6c;
        font-size: 70%;
        margin-left: 30px;
    }
    .socials{
        margin-right: 20px;
        display: flex;
        justify-content: space-between;
        color: #6b6b6c;
        width: 90px;
    }
</style>