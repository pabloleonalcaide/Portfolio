<template>
  <div class="project shadow-large">
      <div class="project-info">
          <h3>{{title}}</h3>
          <p>{{description}}</p>
      </div>
      <div class="project-ref">
          <a :href=link>View Project</a>
      </div>
  </div>
</template>
<script>
export default {
  name: 'Project',
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
.project-info{
    text-align: initial;
}
.project-ref {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #91842f;
    min-width: 15%;
    
    a {
        color: #fff;
        text-decoration: none;
        transition: 1s ease-in;
        &:hover{
            padding-left: 12px;
            text-decoration: underline;
        }
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