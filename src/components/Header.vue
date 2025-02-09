<template>
  <header class="header">
    <div class="logo">
      <a href="/">Praful's Food Delivery</a>
    </div>
    <nav>
      <ul>
        <li><a href="#">Browse Restaurants</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="auth">
      <a href="#">Login</a>
      <a href="#">Sign Up</a>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
}
</script>

<style scoped>
.header {
  background-color: #fff;
  color: #2c3e50;
  padding: 10px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #eee;
}

.logo a {
  font-size: 1.5em;
  font-weight: bold;
  text-decoration: none;
  color: inherit;
}

nav ul {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
}

nav li {
  margin-left: 20px;
}

nav a {
  text-decoration: none;
  color: inherit;
}

.auth a {
  margin-left: 10px;
  text-decoration: none;
  color: inherit;
  border: 1px solid #2c3e50;
  padding: 5px 10px;
  border-radius: 5px;
}
</style>
