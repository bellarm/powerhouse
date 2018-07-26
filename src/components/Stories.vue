<template>
  <div class="home-stories">
    <div class="title">
      STORIES
    </div>
    <div class="subtitle">
      //TODO: decide how a story looks like
    </div>

  </div>
</template>

<script>
export default {
  name: 'Stories'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-stories {
  padding-top: 30px;
  width: 100%;
  height: 80vh;
  background-image: url(../assets/image1.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  overflow: hidden;
  background-attachment: fixed;
  text-align: center;
}

.box {
  margin-top: 30vh;
  padding: 50px 30px 50px 30px;
  float: left;
  background-color: white;
  width: 50%;
}

.title {
  font-size: 60px;
  font-family: 'Oswald', sans-serif;
  color: #FFFFFF;
  text-decoration: underline;
}

.subtitle {
  font-size: 20px;
  font-family: 'Lora', serif;
  color: #FFFFFF;
}

</style>
