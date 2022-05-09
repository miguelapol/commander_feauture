<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-light bg-white">
      <router-link to="/" class="navbar-brand">Feauture FullStack</router-link>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link to="/explorers" class="nav-link">Commanders</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/add" class="nav-link">Agregar Explorer</router-link>
        </li>
      </div>
    </nav>
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>
<script>
export default {
  name: "app"
};
</script>
