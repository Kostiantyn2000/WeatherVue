<template>
  <div class="preloader">
    <div class="preloader-spinner"></div>
  </div>
</template>

<script>

export default {
  name: 'loading',
}
</script>

<style scoped>
.preloader-spinner {
  border: 4px solid #f3f3f3;
  border-top: 4px solid #3498db;
  border-radius: 50%;
  width: 40px;
  height: 40px;
  animation: spin 2s linear infinite;
}

@keyframes spin {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}</style>
  