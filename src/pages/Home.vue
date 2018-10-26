<template>
  <div class="home">
      <HomeTop/>
      <WhoWeAre/>
      <Stories/>
      <Contact/>
  </div>
</template>

<script>
import HomeTop from '@/mycomponents/HomeTop';
import WhoWeAre from '@/mycomponents/WhoWeAre';
import Stories from '@/mycomponents/Stories';
import Contact from '@/mycomponents/Contact';

export default {
  name: 'Home',
  components: {
    HomeTop,
    WhoWeAre,
    Stories,
    Contact
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
