<script setup>
let loggedIn = false;
</script>
<template>
  <div>
    <button v-show="loggedIn">Logout</button>
  </div>
</template>
