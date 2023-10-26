<!-- pages/index.vue -->
<template>
  <div clas="container">
    <div class="main-content">
      <section class="hero">
        <h1 class="title">AboutPage</h1>
      </section>
    </div>
  </div>
</template>

<style scoped>
* {
  border: 1px solid #000;
}

.container {
  background-color: rgb(97, 133, 164);
}
.main-content {
  background-color: #87addf;
  max-width: 100%;
  margin: 0 auto;
  height: 710px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hero {
  text-align: center;
  margin-bottom: 40px;
}

.title {
  font-size: 2.5rem;
  color: #333;
  margin-bottom: 10px;
}

.subtitle {
  font-size: 1.2rem;
  color: #666;
}

.features {
  display: flex;
  justify-content: space-between;
}

.feature {
  flex: 1;
  text-align: center;
  padding: 20px;
  border: 2px solid white;
  border-radius: 8px;
  margin: 0 10px;
}

.feature-title {
  font-size: 1.5rem;
  color: #333;
  margin-bottom: 10px;
}

.feature-description {
  font-size: 1rem;
  color: #666;
}
</style>
