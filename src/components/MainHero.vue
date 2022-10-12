<template>
     <div class="ukraine">
           <p><img width="50px" height="30px" src="../assets/Flag_of_Ukraine.png" alt="">  I stand with Ukraine. &nbsp Donate  <a href="https://bank.gov.ua/en/about/humanitarian-aid-to-ukraine" target="_blank"> & Make an impact</a></p>
    </div>

        <section class="main">
            <div class="main-text">
                <h1>Abin Philip</h1>
                <p>Welcome to my Page!</p>
                <br>
                <p>I am a Software Engineer and  a Frontend Developer born in India and based in 
                    the Great Britain.</p>
                <p>I love exploring and creating new techs.  </p>
                <br>
                <a href="#footer">Contact Me </a>
            </div>

            <div class="hero-image">
                <div class="cube" id="vue"></div>
                <div class="cube" id="javascript"></div>
                <div class="cube" id="html"></div>
                <div class="cube" id="css"></div>
            </div>

        </section>

   
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .ukraine{
        height: 60px;
        background-color: rgb(48, 44, 44);
        font-size: 16px;
        color: rgb(255, 255,255);
        font-family: Ubuntu ;
        display: flex;
    }
    .ukraine img{
        position: relative;
        top: 7px;
    }
    .ukraine p{
        margin: auto auto;
        text-align: center;
    }
    .ukraine a{
        display: inline;
        text-decoration: none;
        color: rgb(255, 255,255);
        font-size: 20px;
        font-weight: 400;
    }
    h1{
        font-family: 'Abril Fatface', cursive;
        font-size: 70px;
        line-height: 70px;
        font-weight: 300;
        margin: 10px 0px;
    }
    h2{
        font-family: 'Abril Fatface', cursive;
        font-size: 40px;
        line-height: 40px;
        font-weight: 300;
        margin:10px 0px;
    }
    p{
        margin: 0;
        font-size: 20px;
        font-family: 'Poppins', sans-serif;
    }
    a{
        color: rgb(162,0,255);
        font-size: 20px;
        text-decoration: none;
        font-weight: 100;
    }
    .main{
        height: 80vh;
        display: flex;
        flex-direction: row;
        align-items: center;
        padding: 30px;
        background-color: #fff;
        position: relative;
        
    }
    .main-text{
        width: 100vw;
        padding: 30px;
        margin-bottom: 100px;
    }
   

    .hero-image{
        position: relative;
        width:40%;
        height: 350px;
        display: block;
        margin-bottom: 100px;
    }

    .hero-image{
        position: relative;
        width:50%;
        height: 350px;
        display: block;
        margin-bottom: 100px;
    }
    .cube{
        position: absolute;
        width: 80px;
        height: 80px;
        /* background-color: pink; */
        transform: rotate(-25deg) skew(25deg);

    }
    .cube::before{
        position: absolute;
        content: "";
        width: 21px;
        height: 100%;
        /* background-color: blue; */
        transform: skewY(-45deg);
        left: -20px;
        bottom: -10px;
    }
    .cube::after{
        position: absolute;
        content: "";
        width: 100%;
        height: 21px;
        /* background-color: rgb(214,23,23); */
        transform: skewX(-45deg);
        left: -10px;
        bottom: -20px;
    }
    #html{
        background-image: url('../assets/html-square.png');
        background-size: cover;
        background-color:rgb(175, 119, 227);
        box-shadow: -50px 60px 20px rgb(50 50 50 / 15%);
        left: 30px;
        bottom: 80px;
    }
    #html::before{
        background-color:rgb(183, 178, 189);
    }
    #html::after{
        background-color:rgb(220, 208, 232);
    }

    #vue{
        background-image: url('../assets/vue_3.png');
        background-size: cover;
        background-color:rgb(46, 148, 85);
        box-shadow: -50px 60px 20px rgb(50 50 50 / 15%);
        left: 130px;
        bottom: 230px;
    }
    #vue::before{
        background-color:rgb(74, 168, 110);
    }
    #vue::after{
        background-color:rgb(112, 186, 140);
    }

    #javascript{
        background-image: url('../assets/javascript-square.png');
        background-size: cover;
        background-color:rgb(224, 224, 7);
        box-shadow: -50px 60px 20px rgb(50 50 50 / 15%);
        left: 200px;
        bottom: -50px;
    }
    #javascript::before{
        background-color:rgb(233, 233, 51);
    }
    #javascript::after{
        background-color:rgb(224, 224, 7);
    }


    #css{
        background-image: url('../assets/css-square.png');
        background-size: cover;
        background-color:rgb(73, 73, 224);
        box-shadow: -50px 60px 20px rgb(50 50 50 / 15%);
        left: 270px;
        bottom: 100px;
    }
    #css::before{
        background-color:rgb(118, 118, 210);
    }
    #css::after{
        background-color:rgb(170, 170, 222);
    }
    @media only screen  and (min-width:970px){
        .square{
            width: 47%;
            margin:1%;
            height: 600px;
        }
        .main-text{
            width: 60vw;
            padding: 10px;
        }   
        .hero-image{
            background-color: #fff;
        }
        
    }

    @media only screen and (max-width:970px) {
            .hero-image{
                display: none;
            }
        }

    /*font-family: 'Abril Fatface', cursive;

    /* font-family: 'Poppins', sans-serif; */
</style>