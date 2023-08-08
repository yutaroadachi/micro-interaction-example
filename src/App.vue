<template>
  <main>
    <h1>Micro Interaction Example</h1>
    <section>
      <LikeButton />
    </section>
  </main>
</template>

<script setup>
import LikeButton from "@/components/LikeButton";
</script>

<style>
* {
  box-sizing: border-box;
}

body {
  background-color: black;
  color: white;
}
</style>

<style scoped>
main {
  padding: 0 16px;
}
</style>
