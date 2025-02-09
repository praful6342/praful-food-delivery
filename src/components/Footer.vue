<template>
  <footer class="footer">
    <div class="footer-content">
      <p>&copy; 2025 Praful's Food Delivery. All rights reserved.</p>
      <nav>
        <ul>
          <li><a href="#">Terms of Service</a></li>
          <li><a href="#">Privacy Policy</a></li>
          <li><a href="#">Contact</a></li>
        </ul>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter',
}
</script>

<style scoped>
.footer {
  background-color: #f8f8f8;
  color: #2c3e50;
  padding: 20px;
  text-align: center;
  border-top: 1px solid #eee;
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
  margin: 10px 0 0;
  padding: 0;
}

nav li {
  margin: 0 10px;
}

nav a {
  text-decoration: none;
  color: inherit;
}
</style>
