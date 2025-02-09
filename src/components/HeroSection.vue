<template>
  <div class="hero">
    <div class="hero-content">
      <h1>Craving Something Delicious?</h1>
      <p>Order from your favorite local restaurants and get fast delivery!</p>
      <div class="search-box">
        <input type="text" placeholder="Enter your address or restaurant..." />
        <button>Find Food</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroSection',
}
</script>

<style scoped>
.hero {
  background: url('your-food-image.jpg') center/cover no-repeat; /* Replace with your image */
  height: 500px; /* Adjust as needed */
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: white;
}

.hero-content {
  background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent overlay */
  padding: 20px;
  border-radius: 10px;
}

h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.search-box {
  display: flex;
  justify-content: center;
}

input[type='text'] {
  padding: 10px;
  width: 300px;
  border: none;
  border-radius: 5px 0 0 5px;
  font-size: 1em;
}

button {
  padding: 10px 20px;
  background-color: #ff6600; /* Example color */
  color: white;
  border: none;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
  font-size: 1em;
}
</style>
