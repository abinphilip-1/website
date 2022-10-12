<template>
    <section class="two">
        <h3>Some stuffs about mee...!!!</h3>
        <p class="intro">I have strong frontend knowledge and experience with excellent knowledge of
             javascript and
             single page App frameworks using Vue js, PWA, add desktop app using electron js by consuming
              Rest Api.
         </p>
        
        <p>Masters Degree in Computer Science, 5 years of experience in javascript development.
        Produce fully responsive solutions, write clean code. Write test scripts, DevOps tools,
         CI/CD pipeline.  
        </p>
        <p>Convert UI designs /UX wireframes in HTML5  CSS3  and javascript. Collaborate with various
             stakeholders to deliver state of the art standards and complete sprint commitments. 
            Participate in all project stages and lead to successful completion of  projects.
            Working in Test Driven Environment  Agile Environment.

        </p>
        <!-- <h5>JSON, asynchronous javascript, NoSQL, SQL, CSS3, Flex, Grid, Materialize, Bootstrap, Firebase, node , npm , express, embedded js , partial views,  bash , webpack, babel, Azure Devops, Jira, Confluence , GIT, GitHub. Progressive web apps, Electron js desktop app,
            Vue ecosystem: VueJs, Vuex, Router, Nuxt js, 
            Docker JQuery, 
                Chrome Devtools, Vue dev tools, lighthouse audit.
        </h5> -->
  </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .two{
        background-color: rgb(0,0,0);
        height: 760px;
        position: relative;
        /* padding:30vh; */
        clip-path: polygon(0 0, 100% 0, 100% calc(100% - 10vw), 0 100%);
    }
    .two::after{
    content: '';
    background:  rgb(0,0,0);
    height: 150px;
    width: 150px;
    position:absolute;
    bottom: -1em;
    z-index: 100;
    transform: skew(0,-20deg);
    }
    .two::before{
    content: '';
    background:  rgb(0,0,0);
    height: 150px;
    width: 150px;
    position:absolute;
    bottom: -1em;
    z-index: 100;
    right: 50%;
    transform: skew(0,20deg);
    }

    .intro{
        
        margin: 0px;
        color:#fff;
    }
    h3{
        padding-top: 80px;
        color:#fff;
    }
    h5{
        color:#fff;
    }
    section p{
        color:#fff;
        padding-left: 7vw;
        padding-right: 7vw;
    }
    @media screen and (min-width:576px) {
        section p{
            padding-left: 7vw;
            padding-right: 7vw;
            color:#fff;
        }
        section p:first-child{
            padding-left: 7vw;
            padding-right: 7vw;
        }
        .two{
            height: 560px;
        }
    }
</style>