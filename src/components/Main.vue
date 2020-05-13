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
<style lang="scss" scoped>
.main-container {
  font-family: 'Livvic', sans-serif;
  max-width: 1200px;
  margin: auto;
}
.spacer {
    height: 20px;
}

@media screen and (min-width: 768px) {
  .spacer {
    height: 60px;
  }
}
</style>