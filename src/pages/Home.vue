<template>
  <div class="home">
    <HomeTop/>
    <WhoWeAre/>
    <Stories/>
    <Contact/>
  </div>
</template>

<script>
import HomeTop from '@/components/HomeTop'
import WhoWeAre from '@/components/WhoWeAre'
import Stories from '@/components/Stories'
import Contact from '@/components/Contact'

export default {
  name: 'Home',
  components: {
    HomeTop,
    WhoWeAre,
    Stories,
    Contact
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
