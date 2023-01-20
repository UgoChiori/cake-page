<template>
  <!-- <div> -->
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/cakes">Gallery</router-link> |
    <router-link to="/contact">Contact</router-link>
  </div>

  <div id="footer">
    <footer>
      <p>&copy; 2018 - 2019</p>
      <p><a href="">Privacy Policy</a> | <a href="">Terms of Use</a></p>
      <p>
        <a href="">Contact Us</a>
      </p>
    </footer>
  </div>
  <!-- </div> -->
  <router-view />
</template>
<script></script>
<!-- Component { CakeView, HomeView, AboutView, ContactView } -->
<style>
body {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: black;
  margin-top: 60px;

}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
