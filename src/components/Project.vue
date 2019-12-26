<template>
  <div class="project shadow-large">
      <div class="project-image">
          <img :src="image" />
      </div>
      <div class="project-info">
          <h3>{{title}}</h3>
          <p>{{description}}
          </p>
          <a :href=link>View Project</a>
      </div>
  </div>
</template>
<script>
export default {
  name: 'Project',
  data(){
      return{
          image: require('@/assets/project.jpg')
      }
  },
  props: [
        'title',
        'description',
        'link'
        ]
}
</script>
<style lang="scss" scoped>

$heading: #333333;
$text: #74808a;

.project-image {
    flex: 0 0 20em;
    img{
        width: 100%
    }
}

.project-info {
    padding: 15px;

    h3 {
        font-size: 1.5em;
        font-weight: 300;
        color: $heading;
        margin: 0 0 15px 0;
    }

    p {
        color: $text;
        margin: 0 0 15px 0;
        font-size: 0.9em;
    }
}
</style>