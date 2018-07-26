<template>
  <div class="home-top">
    <div class="box">
      <div class="title">
        POWERHOUSE
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
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Lora');

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
  margin-top: 30vh;
  margin-left: 5px;
  padding: 50px 30px 50px 30px;
  float: left;
  background-color: white;
  width: 50%;
}

.title {
  font-size: 60px;
  font-family: 'Oswald', sans-serif;
  color: #000000;
}

.subtitle {
  font-size: 20px;
  font-family: 'Lora', serif;
  color: #000000;
}

</style>
