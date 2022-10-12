<template>
    <div class="three ">
        <h1>Demo Works</h1>
        <div class="flex-container">
            <div class="square calc">
                <img src="../assets/calc2.png" alt="" height="250px">
                <p><b>Core techs:</b> vue, vuex, </p>
            </div>
            <div class="square gym">
               <img src="../assets/fitness_gym.png"  height="200px" width="250px" alt="">
               <p><b>Core techs:</b> vue, vue,vue router, rest api, materialize css </p>
            </div>
            <div class=" square ukrail">
                <img src="../assets/railstation.png" alt="" height="250px">
                <p><b>Core techs:</b> vue, vuex, axiox, vue router, Bootstrap </p>
                <p>Get arrival and departure at a station</p>
            </div>
    </div>
    </div>
   
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .three{
    background: #fff;
    padding-top: 70px;
    min-height: 70vh;
    }
    h1{
        font-family: 'Abril Fatface', cursive;
    }
    p{
        font-family: 'Poppins', sans-serif;
        font-size: 14px;
    }
    .flex-container{
        display: flex;
        background-color: #fff;
        flex-flow: column; 
    }
    .gym p{
        position: relative;
         /* bottom: -3em; */
    }
    .square {
        background-color: #ddd;
        padding: 15px;
        border-radius: 15px;
        margin: 5px;
    }
    @media screen and (min-width:576px) {
        .flex-container{
            flex-flow: col;
            justify-content: space-around;
        }
    }
    @media screen and (min-width:768px) {
        .flex-container{
            flex-flow: row;
            justify-content: space-around; 
        }
        .gym p{
            position: relative;
            bottom: -3em;
        }
    }
</style>

