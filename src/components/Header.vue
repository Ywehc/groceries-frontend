<template>
  <div class="header-container">
    <div class="logo-container">
      <div class="upper-logo">
        <h2 class="quick">Q</h2>
        <h2 class="quick">u</h2>
        <h2 class="quick">i</h2>
        <h2 class="grocery">
            Grocery
        </h2>
      </div>
      <div class="lower-logo">
        <h2 class="k">k</h2>
        <!-- <i class="fas fa-carrot"></i> -->
      </div>
      
    </div>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

.header-container {
  min-height: 100vh;
  font-family: 'Rokkitt', serif;
  color: $green-light;
  text-align: center;
  font-size: 40px;
  line-height: 28px;
  position: relative;
  margin: auto;
}
.logo-container {
  position: absolute;
  padding: 14px;
  width: 100%;
}

.quick {
  color: $gold-light;
  margin-left: 188px;
}
.k {
  display: inline-block;
  color: $gold-light;
  margin-left: 188px;
}
.grocery {
  margin-left:182px;
  margin-top: -6px;
  letter-spacing: 2px;
}
.fa-carrot {
  font-size: 20px;
  margin-left: 10px;
}
</style>