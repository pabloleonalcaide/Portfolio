<template>
  <div>
    <h3>{{work.role}}</h3>
    <h4><b>{{work.name}}</b> {{work.period}}</h4>
    <p>
      {{work.description}}
    </p>
  </div>
</template>
<script>
export default {
name: 'ExperienceItem',
props: [
  'work'
]
}
</script>
<style lang="scss" scoped>
  $background: #fff;
  $border: #dcd9d9;
  $heading: #333333;
  $text: #74808a;
  div {
    background: $background;
    padding: 15px;
    margin: 10px;
    border: 1px solid $border;

    h3 {
        font-size: 1.5em;
        font-weight: 300;
        color: $heading;
        display: inline-block;
        margin: 0;
    }

    h4 {
        font-size: 1.2em;
        font-weight: 300;
        color: #7e8890;
        margin: 0 0 15px 0;
    }

    p {
        color: $text;
        font-size: 0.9em;
        margin: 0;
    }
  }
</style>