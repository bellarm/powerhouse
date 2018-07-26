<template lang="html">
  <nav class="navbar">
    <div class="nav-elem brand">
      <router-link tag="a" :to="{ name: brand.name }">{{ brand.text }}</router-link>
    </div>
      <div :class="['nav-elem']" v-for="link in links" :key="link.text">
        <router-link tag="a" :to="{ name: link.name }">{{ link.text }}</router-link>
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
  margin-bottom: 10px;
  border-bottom: 1px solid black;
  display: flex;
  align-items: flex-end;
  justify-content: flex-start;
  font-family: 'Sunflower', sans-serif;
}

.nav-elem {
  margin-left: 20px;
  color: #000000;
}

.nav-elem a {
  color: #000000;
}

.brand a {
  font-size: 40px;
  font-family: 'Oswald', sans-serif;
  color: #000000;
}

</style>
