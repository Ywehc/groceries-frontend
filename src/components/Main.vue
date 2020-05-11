<template>
  <div class="main-container">
      <Controls /> 
      <div class="spacer"></div>
      <List />    
  </div>
</template>

<script>
import Controls from './Controls.vue'
import List from './List.vue'

export default {
    components: {
    Controls,
    List
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
    .spacer {
        height: 20px;
    }
</style>