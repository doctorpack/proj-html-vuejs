<template>
    <div>
        <div class="container">
            <!-- BANNER -->
            <section class="banner">
                <div>
                <h1 class="text-banner">Music is Life</h1>
                    <hr class="divisore">
                <h6 class="subtext-banner">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad commodi nobis minima error, quasi eveniet saepe soluta alias voluptates aliquam. Vitae quos illum sed eos ad facilis quo, aut cum?</h6>

                </div>
            </section>
            <!-- MAIN SECTION -->
            <section class="central-color">
                <div class="main-subtitle-2">
                    <h4>Latest Band News</h4>
                    <hr class="divisore-2">
                    <h6 class="sub-text-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad commodi nobis minima error, quasi eveniet saepe soluta alias voluptates aliquam. Vitae quos illum sed eos ad facilis quo, aut cum?</h6>
                </div>
            
                <div class="illustration-zone">
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog_music_techo-1200x600.jpg" alt="techno">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">technology and music</span>
                            <span class="sub-text-color-fix">Sed sit amet sem turpis. curabitur cursus lacinia est at interdum risus id condimentum</span>
                        </div>
                    </div>
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog-post1-400x600.jpg" alt="blog-spot">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">taking it back to the old school</span>
                            <span class="sub-text-color-fix">sed sit amet sem turpis. Curabitur cursus lacina est at interdum risus id condimentum</span>
                        </div>
                    </div>
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog-post3-600x900.jpg" alt="guitars">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">while my guitar gently weeps</span>
                            <span class="sub-text-color-fix">sed sit amet sem turpis. Curabitur cursus lacina est at interdum risus id condimentum</span>
                        </div>
                    </div>
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog-post4-600x900.jpg" alt="guitars">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">it just sounds better</span>
                            <span class="sub-text-color-fix">sed sit amet sem turpis. Curabitur cursus lacina est at interdum risus id condimentum</span>
                        </div>
                    </div>
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog-post2-600x900.jpg" alt="guitars">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">sharing the stage with a legend</span>
                            <span class="sub-text-color-fix">sed sit amet sem turpis. Curabitur cursus lacina est at interdum risus id condimentum</span>
                        </div>
                    </div>
                    <div class="illustration">
                        <div>
                            <img src="../assets/img/blog_flavor_rock-1200x600.jpg" alt="guitars">
                        </div>
                        <div class="illustration-text">
                            <span class="illustration-name">the flavor of rock</span>
                            <span class="sub-text-color-fix">sed sit amet sem turpis. Curabitur cursus lacina est at interdum risus id condimentum</span>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <!-- JUMBOTRON 2 -->
        <div class="latest-news-background">
            <h2 class="latest-news-text">VIEW AT LATEST NEWS</h2>
        </div>
        <div class="container-central">
            <div class="fix-central">
                <p class="central-text">i just listened to it and said to myself,"Man, i really love this album."Still,today.it just sounds so fresh.it sounds full of ideas.These guys knew what they were doing.They're good.And they're inventive.I haven't heard anything this year that's as inventive.i don't really expect to</p>
                <img class="play-button" src="../assets/img/band_interview_play_icon.png" alt="">
            </div>
        
        </div>
        <!-- LIVES DATE SECTION -->
        <div class="lives-date-background">
            <div class="main-subtitle-2">
                    <h4>Live dates</h4>
                    <hr class="divisore-2">
                    <h6 class="sub-text-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad commodi nobis minima error, quasi eveniet saepe soluta alias voluptates aliquam. Vitae quos illum sed eos ad facilis quo, aut cum?</h6>
                </div>
        </div>
        <!-- NEWS SECTION -->
        <div class="latest-news-background">
            <h2 class="latest-news-text">VIEW ALL LIVES DATES</h2>
        </div>
   
    </div>
</template>

<script>

</script>

<style lang="scss" scoped>
    @import "../assets/scss/common.scss";
    // BANNER
    .central-color{
        background-color: #292d39;
    }
    .sub-text-2{
        margin-bottom: 50px;
        text-align: center;
        max-width: 60%;
        text-align: center;
        font-size: 10px;
        margin: auto;
        color: #6b6b6c;
    }
    .divisore{
        width: 80px;
        align-self: center;
        color: #191b21;
        border-color: #191b21;
    }
    .divisore-2{
        margin-left: 47%;
        width: 80px;
        color: #191b21;
        border-color: #191b21;
    }
    .container-central{
        background-image: url(../assets/img/home-testimonial-parallax.jpg);
        height: 30rem;
        max-width: 100%;
        background-size: cover;
        display: flex;
    
    }
    .fix-central{
        text-align: center;
        margin: auto;
        width: 45%;
        color: rgba(255, 255, 255, 0.806);
    }
    .play-button{
        margin-top: 40px;
    }
    .central-text{
        text-align: center;
        margin: auto;
        color: rgba(255, 255, 255, 0.806);  
    }
    .play-button{
        height: 50px;
        width: 50px;
    }
    .text-banner{
        color: white;
    }
    .subtext-banner{
        color: #6b6b6c;
    }
    .banner{
        width: 100%;
        height: 200px;
        text-align: center;
        background-color: #272b34;
    }
    .banner div{
        flex-direction: column;
        height: 100%;
        width: 65%;
        display: flex;
        justify-content: center;
        margin: auto;
        
        
    }
    .banner-content{
        height: 100%;
        background-color: white;
        border: 1px solid grey;
        border-radius: 25px;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    // MAIN SECTION
    .main-subtitle h2{
        font-size: 1.5rem;
        text-align: center;
        color: white;
    }
    .main-subtitle-2{
        font-size: 1.5rem;
        text-align: center;
        color: white;
    }
    // DISHES
    .illustration-zone{
        display: flex;
        justify-content: space-between;
        margin: auto;
        max-width: 70%;
        flex-wrap: wrap;
    
    }
    .illustration{
        width: calc(95% / 3);
        background-color:#35353f;
    }
    .illustration-text span{
        display: block;
        text-align: center;
    }
    .illustration-name{
        color: #ea4a56;
        font-size: 1rem;
        margin: 10px;
    }
    .sub-text-color-fix{
        font-size: 0.5rem;
        color:#6b6b6c;
    }
    // JUMBOTRON2
    .latest-news-background{
        height: 100px;
        background-color: #ea4a56;
        display: flex;
        text-align: center;
    }
    .latest-news-text{
       text-align: center;
       margin: auto;
       font-size: small;
       color: white;
    }
  
    
    .card{
        height: calc(90% / 2);
        width: calc(90% / 4);
        position: relative;
    }
    .card span{
        color: white;
        font-weight: bold;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%);
    }
  
    // ORDERING APP SECTION
    .lives-date-background{
        background-color: #272b34;
        background-size: cover;
        height: 600px;
    }
   
   
    // NEWS SECTION
    .news-adjustments{
        padding-top: 150px;
        padding-bottom: 100px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .news-cards{
        margin-bottom: 150px;
        display: flex;
        justify-content: space-between;
    }
    .news-card{
        width: calc(90% / 2);
        text-align: center;
    }
    .news-card h2{
        font-size: 2.3rem;
        margin: 1rem 0;
    }
</style>