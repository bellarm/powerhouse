<template>
  <div id="app" class="flyout">
    <navbar position="top" class="default-color" scrolling dark>
      <mdb-navbar-brand href="#/">
        <img src="@/assets/powerhouse.jpg" height="30" alt="">
      </mdb-navbar-brand>
      <navbar-collapse>
        <navbar-nav right>
          <navbar-item router exact href="/" waves-fixed>Home</navbar-item>
          <navbar-item router href="/css" waves-fixed>About</navbar-item>
          <navbar-item router href="/components" waves-fixed>Stories</navbar-item>
          <navbar-item router href="/advanced" waves-fixed>Contact</navbar-item>
        </navbar-nav>
      </navbar-collapse>
    </navbar>
    <main :style="{marginTop: '60px'}">
      <router-view></router-view>
    </main>
    <Footer class="font-small">
      <p class="footer-copyright mb-0 text-center">
        &copy; {{new Date().getFullYear()}} Powerhouse City</a>
      </p>
    </Footer>
  </div>
</template>

<script>
import { Navbar, NavbarItem, NavbarNav, NavbarCollapse, mdbNavbarBrand, Footer } from 'mdbvue';

export default {
  name: 'app',
  components: {
    Navbar,
    NavbarItem,
    NavbarNav,
    NavbarCollapse,
    mdbNavbarBrand,
    Footer
  }
};

</script>

<style>
.flyout {
	display:flex;
	flex-direction: column;
	min-height:100vh;
	justify-content: space-between;
}

.active {
  background-color: rgba(255, 255, 255, 0.1);
}

</style>
