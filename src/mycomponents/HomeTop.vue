<template>
  <div class="home-top">
    <div class="box">
      <div class="title">
        P O W E R H O U S E
      </div>
      <div class="subtitle">
        Together, we’re taking back this city campus by campus,
        block by block, and having a whole lot of fun along the way.
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeTop'
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lato');

.home-top {
  width: 100%;
  height: 95vh;
  background-image: url(../assets/bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  overflow: hidden;
  background-attachment: fixed;
}

.box {
  margin-top: 40vh;
  margin-right: 20vh;
  margin-left: 20vh;
  /*background-color: rgb(255,255,255,0.2);*/
}

.title {
  font-size: 56px;
  font-family: 'Lato', sans-serif;
  font-weight: 800;
  color: #fff;
}

.subtitle {
  font-size: 22px;
  font-family: 'Lato', serif;
  color: #fff;
}

</style>
