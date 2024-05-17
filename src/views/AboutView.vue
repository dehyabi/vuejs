<template>
  <div>
    <TwoInOne :name="'Welcome to About Page'" :imgsrc="cat" :visit="'/services '" :btnName="'Services'" />
  </div>
</template>

<script setup>
import TwoInOne from "../components/TwoInOne.vue";
import cat from "../assets/images/cat.jpg";
</script>

<style scoped></style>
