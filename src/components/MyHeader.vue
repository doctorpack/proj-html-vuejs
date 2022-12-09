<template>
    <div class="header-background">
        <div class="container">
            <!-- LOGO + NAV SECTION -->
            <section class="header-content">
                <!-- LOGO -->
                <div>
                    <a href="#"><img src="../assets/img/avada-music-logo.png" alt="logo"></a>
                </div>
                <!-- NAVBAR -->
                <nav>
                    <ul class="navbar">
                        <li @click="setActiveMenuVoice(index)" v-for="option,index in navbarOptions"  :key="index"><a :class="activeMenuVoice === index ? 'active' : ''" href="#" v-html="option"></a></li>
                    </ul>
                </nav>
            </section>
            <!-- JUMBOTRON SECTION -->
            <section class="jumbotron-adjustments">
                <div class="jumbotron-container">
                    <div>
                        <span class="jumbotron-first-text">Untold Stories</span>
                    </div>
                    <div>
                        <span class="jumbotron-second-text"><span>there is an untold story behind every favorite song</span></span>
                    </div>
                    <div class="button-container">
                        <a href="#"><span class="button">latest album  </span></a>
                        <a href="#"><span class="button">live dates  </span></a>
                    </div>
                </div>
            </section>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return{
                activeMenuVoice: 0,
            }
        },
        methods:{
            // FUNCTION THAT SETS ACTIVE NAV ELEMENT
            // ToDo:prevent page reload when clicking a nav element
            setActiveMenuVoice(index){
                this.activeMenuVoice = index;
            }
        },
        props:{
            navbarOptions: Array,
        }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/common.scss";
    // COMMON
    a{ 
        font-weight: bold;
        color: white;
    }
    .header-background{
        background-image: url(../assets/img/home_slider.jpg);
        background-size: cover;
        background-repeat: no-repeat;
    }
    .header-content{
        
        display: flex;
        justify-content: space-between;
    }
    // LOGO
    .header-content div{
        width: 30%;
    }
    .header-content div img{
        width: 250px;
    }
    // NAVBAR
    nav{
        display: flex;
        align-items: center;
        width: 50%;
    }
    .navbar{
        display: flex;
        justify-content: space-between;
        width: 100%;
    }
    // ACTIVE CLASS
    .active{
        color: $color-cube-9;
    }
</style>