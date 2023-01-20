<template>
  <!-- <div> -->
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/cakes">Gallery</router-link>
    <router-link to="/contact">Contact</router-link>
  </div>

  <!-- <div id="footer">
    <footer>
      <p>&copy; 2018 - 2019</p>
      <p><a href="">Privacy Policy</a> | <a href="">Terms of Use</a></p>
      <p>
        <a href="">Contact Us</a>
      </p>
    </footer>
  </div> -->
  <!-- </div> -->
  <router-view />
</template>
<script></script>
<!-- Component { CakeView, HomeView, AboutView, ContactView } -->
<style>
@import url("https://fonts.googleapis.com/css2?family=Outfit:wght@100;200;300;400;500;600;700;800;900&display=swap");

* {
  margin: 0;
  padding: 0;
  font-family: "Outfit", sans-serif;
  text-align: center;
}

h1 {
  color: black;
}

#nav {
  display: flex;
  justify-content: space-around;
  /* align-items: right; */
  padding: 10px;
  background-color: white;
}

#nav a {
  color: black;
  text-decoration: none;
  padding: 10px;
  font-size: 30px;

  /* align-items: right; */
}

#nav a.router-link-exact-active {
  color: grey;
}

@media (max-width: 768px) {
  #nav {
    justify-content: space-between;
    padding: 10px;
  }
  #nav a {
    font-size: 20px;
  }
}
</style>
