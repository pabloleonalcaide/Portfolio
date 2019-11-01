<template>
    <div id="projects" class="background-alt">
        <h2 class="heading">Projects</h2>
        <div class="container">
            <div class="row">
                <Project 
                  title="Tweepy"
                  description="Project developed together with my study partner @nievesborrero to put into practice our learning about Python, applying it to the treatment of data obtained from Twitter"
                  link="https://github.com/tweepy-sysmana/sysmana2018"
                />
                <Project 
                  title="Chatbot & Admin panel"
                  description="Chatbot developed in Dialogflow, managed in a management panel using NodeJs and Handlebars.js, as well as the APIs of Google Action, Giphy and Dialogflow"
                  link="https://github.com/Proyecto-chatbot/panel-administracion-chatbot"
                />
            </div>
        </div>
    </div>
</template>
<script>
import Project from './Project'
export default {
  name: 'Projects',
  components: {
    Project
  }
}
</script>
<style lang="scss" scoped>
.project {
    position: relative;
    max-width: 900px;
    margin: 0 auto 30px auto;
    overflow: hidden;
    background: #fff;
    border-radius: 4px;
    display: flex;
}

</style>