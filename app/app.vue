<template>
  <div class="container">
    <NuxtRouteAnnouncer />
    <div class="no-text">No</div>
  </div>
</template>

<style scoped>
.container {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0;
  padding: 0;
  background-color: #1a1a1a;
}

.no-text {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-size: 120px;
  font-weight: bold;
  color: red;
}
</style>
