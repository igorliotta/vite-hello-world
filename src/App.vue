<script>
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!',
    }
  },
  methods: {

  }
}
</script>

<template>
  <div class="title-container">
    <h1 class="title">{{ message }}</h1>
  </div>
</template>

<style scoped>

.title-container {
  width: 800px;
  height: 200px;
  border-radius: 10px;
  background-color: blue;
  opacity: 0.4;
  display: flex;
  justify-content: center;
  align-items: center;
}
.title {
  font-size: 42px;
  color: aqua;
}
</style>
