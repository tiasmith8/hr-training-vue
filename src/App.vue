<template>
  <header>
    <!-- Normal html element (nav) -->
    <nav>
      <ul>
        <li class="nav-item">
          <img class="logo" src="./assets/hr-icon.png" />
          HR Training
        </li>
      </ul>
    </nav>
  </header>
  <main>
    <HomePage />
  </main>
</template>

<script>
import HomePage from './domain/home/homePage.vue';

export default {
  name: 'App',
  components: {
    HomePage,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fiixed;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

main {
  margin: 0 auto;
  /* This will center the main content */
  padding: 30px;
  background-color: white;
  width: 1024px;
  min-height: 300px;
}

header {
  background-color: #999;
  width: 1084px;
  margin: 0 auto;
}

ul {
  padding: 3px;
  display: flex;
}

.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}

.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
