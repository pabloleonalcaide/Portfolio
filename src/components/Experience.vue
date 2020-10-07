<template>
    <div id="experience" class="background-alt">
        <h2 class="heading">Where I've been working on</h2>
        <div id="experience-timeline">
            <ExperienceItem
              v-for="(item, index) in works"
              v-bind:key="index"
              v-bind:work="item"
            />
        </div>
    </div>
</template>
<script>
import ExperienceItem from './ExperienceItem'
export default {
  name: 'Experience',
  components: {ExperienceItem},
  data() {
    return {
        works: [
            {name:"Atmira Espacio de Consultoría",role:"Mid Software Developer",period:"2020-Present",
            description:"Webb apps development with SpringBoot and Angular in a project with multiple external contributors"},
            {name:"Redsys ",role:"Junior Software Developer",period:"2018-2020",
            description:"Development of applications with Java (JEE), Spring Framework and Angular in an environment of agile methodologies"},
            {name:"Signlab Nuevas Tecnologías",role:"Junior Software Developer",period:"2018",
            description:"Web apps development with PHP (CodeIgniter), JS (VueJS), and corporate websites with Wordpress"}
        ]
    }
}
}
</script>
<style lang="scss" scoped>

$background: #fff;
$base-color: #3498db;
$border: #dcd9d9;
$heading: #333333;
$text: #74808a;

#experience {
    padding: 50px 15px;
    text-align: center;
    border-bottom: 1px solid $border;
}

#experience-timeline {
    margin: 30px auto 0 auto;
    position: relative;
    max-width: 1000px;
    display: flex;
    &:before, &:after {
        content: none;
    }
}
@media only screen and (max-width : 480px){
    #experience-timeline{
        flex-direction: column;
    }
}

</style>