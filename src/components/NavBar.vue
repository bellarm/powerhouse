<template lang="html">
  <nav class="navbar">
    <router-link tag="a" :to="{ name: brand.name }" class="brand">{{ brand.text }}</router-link>
    <div class="navbar-right">
    <template v-for="link in links">
      <router-link tag="a" :to="{ name: link.name }">{{ link.text }}</router-link>
    </template>
  </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  data() {
    return {
      links: [
        {
          name: 'Home',
          text: 'HOME',
          style: ''
        },
        {
          name: 'About',
          text: 'WHO WE ARE',
          style: ''
        },
        {
          name: 'About',
          text: 'STORIES',
          style: ''
        },
        {
          name: 'About',
          text: 'CONTACT',
          style: ''
        }
      ],
      brand: {
        name: 'Home',
        text: 'POWERHOUSE'
      }
    }
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Oswald|Sunflower:300');

.navbar {
  border-bottom: 2px solid black;
  font-family: 'Sunflower', sans-serif;
  overflow: hidden;
  position: relative;
}

.navbar a {
  margin-left: 10px;
  margin-right: 10px;
  color: #000000;
}

.brand {
  font-size: 30px;
  font-family: 'Oswald', sans-serif;
  color: #000000;
}

.navbar-right {
  position: absolute;
  bottom: 0;
  right: 0;
}

</style>
