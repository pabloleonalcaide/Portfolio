<template>
    <div id="skills" class="background-alt">
        <h2 class="heading">Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>Spring</li>
            <li>JavaScript</li>
            <li>Vue</li>
            <li>Python</li>
            <li>PHP</li>
            <li>CodeIgniter</li>
            <li>Git</li>
        </ul>
        <!-- Learning TDD, DDD, Testing... Related to Courses-->
    </div>
</template>
<script>
export default {
  name: 'Skills'
}
</script>
<style lang="scss">

$base-color: #3498db;
$heading: #374054;

#skills {
    padding: 50px 15px;
    text-align: center;

    h2 {
        color: $heading;
        margin-bottom: 50px;
    }

    ul {
        display: flex;
        flex-wrap: wrap;
        padding: 0;
    }

    li {
        margin: 10px auto;
        padding: 5px 10px;
        list-style: none;
        overflow: hidden;
      
        border-width: 0;
        outline: none;
        border-radius: 2px;
        box-shadow: 0 1px 4px rgba(0, 0, 0, .6);
        
        background-color:$base-color;
        color: #ecf0f1;
        
        transition: background-color .3s;
        &:hover, &:focus {
            background-color: darken($base-color, 25%);
          }    
    }
}
</style>