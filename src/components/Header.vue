<template>
  <div class="header-container">
    <div class="logo-container">
      <div class="upper-logo">
        <h2 class="quick q">Q</h2>
        <h2 class="quick u ">u</h2>
        <h2 class="quick i">i</h2>
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

<style lang="scss" scoped>

.header-container {
  height: 160px;
  background: $dark;
  font-family: 'Rokkitt', serif;
  color: $green-light;
  text-align: center;
  font-size: 40px;
  line-height: 28px;
  margin: auto;
}
.logo-container {
  display: flex;
  flex-direction: column;
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

@media screen and (min-width: 768px) {
  .grocery {
    margin-left: 30px;
    text-align: left;
  }
  .logo-container {
    display: flex;
    text-align: left;
    padding-top: 30px;
  }
  .q {
    margin-left: 94px;
  }
  .u{
    margin-left: 98px;
  }
  .i {
    margin-left: 102px;
  }
  .k {
    margin-left: 98px;
  }
}
</style>