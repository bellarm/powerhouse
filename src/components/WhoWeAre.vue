<template>
  <div class="home-about">
    <div class="title">
      WHO WE ARE
    </div>
    <div class="subtitle">
      Can do like 3 columns for every event
    </div>

  </div>
</template>

<script>
export default {
  name: 'WhoWeAre'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home-about {
  padding-top: 30px;
  padding-bottom: 30px;
  width: 100%;
  overflow: hidden;
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
  color: #000000;
  text-decoration: underline;
}

.subtitle {
  padding: 10px 10px 10px 10px;
  font-size: 20px;
  font-family: 'Lora', serif;
  color: #000000;
}

</style>
