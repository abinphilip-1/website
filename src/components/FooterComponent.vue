<template>
    <div id="footer">
        <div class="sub sec1">
            <h3>Lets have a Chat.!!!</h3>
        </div>
        <div class="sub sec2">
            <div class="mail">
                <img src="../assets/icons8-mail-60.png" alt="">
                <a href="mailto:tabinphilip@gmal.com">tabinphilip@gmail.com</a>
                
            </div>
            <div class="linkedin">
                <img src="../assets/icons8-linkedin-64.png" alt="">
                <a href="https://www.linkedin.com/in/abin-philip-m/">abin-philip-m</a>
            </div>

            <div class="git">
                <img src="../assets/icons8-github-60.png" alt="">
                <a href="https://github.com/abinphilip-1">abinphilip-1</a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    #footer{
        background-color: rgb(0,  0, 0);
        padding-top: 5vh;
        color: #fff;
        display: flex;
        justify-content: space-around;
        min-height: 25vh;
        flex-wrap: wrap;
    }
    .sub{
        min-height: 20vh ;
        width: 100vw;
        text-align: center;
        align-items: center;
    }
    .sec2{
        margin-bottom: 5px;
        position: relative;
        top:-2em;

    }
    .sec2 a{
        color: #fff;
        text-decoration: none;
        margin-left: 10px;
    }
    .mail{
        position: relative;
    }
    .mail img{
        background-color: #fff;
        width: 35px;
        border-radius: 10px;
        position: relative;
        bottom: -.7em;
        padding: 2px;
    }
    .linkedin{
        position: relative;
        padding-top: 5px;
    }
    .linkedin img{
        background-color: #fff;
        width: 35px;
        border-radius: 10px;
        position: relative;
        bottom: -.7em;
        left: -2.2em;
        padding: 2px;
    }
    .linkedin a{
        left:-2em;
    }

    .git{
        position: relative;
        padding-top: 5px;
    }
    .git img{
        background-color: #fff;
        width: 35px;
        border-radius: 10px;
        position: relative;
        bottom: -.7em;
        left: -2.5em;
        padding: 2px;
    }

    @media screen  and (min-width:576px){
        .sub{
            height: 19vh ;
            width: 40vw;
            text-align: center;
            align-items: center;
        }
        .sec1{
            position: relative;
            bottom: -2.5em;
        }
        .sec2{
            position: relative;
            top:0em;
    }
    }

</style>