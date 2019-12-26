<template>
    <li>
        <a 
        :href=link
        target="_blank">
          <i 
            class="fa"
            :class="iconClass"
            aria-hidden="true">
          </i>
        </a>
    </li>
</template>
<script>
export default {
  name: 'SocialIcoList',
  props:[ 
    'link',
    'iconClass'
    ]
}
</script>
<style lang="scss">

</style>