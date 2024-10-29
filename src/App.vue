<script setup></script>
<template>
  <p><strong>Current route path:</strong> {{ $route.fullPath }}</p>
  <nav>
    <RouterLink to="/">Go to Home</RouterLink>
    <RouterLink to="/about">Go to About</RouterLink>
  </nav>
  <main>
    <RouterView />
  </main>
</template>
<style scoped>
main{
  width: 100%;
  background: #eee;
  height: 100%;
  margin: 0;
  padding: 0;
  position: absolute;
  top:0;
  bottom: 0;
  right: 0;
  left: 0;
}
</style>
