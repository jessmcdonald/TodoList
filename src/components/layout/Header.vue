<template>
  <header class="header">
    <h1>TodoList</h1>
    <div id="app">
      <div class="nav">
        <router-link class="nav-item" to="/">Home</router-link>|
        <router-link to="/about">About</router-link>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  background: #333;
  text-align: center;
  padding: 10px;
}

.header a {
  color: #fff;
  padding-right: 5px;
  text-decoration: none;
}

h1 {
  color: #fff;
}

.nav {
  color: rgb(181, 32, 201);
}
</style>
