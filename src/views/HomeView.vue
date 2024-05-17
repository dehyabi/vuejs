<template>
  <div>
    <TwoInOne :name="'Do you like cat?'" :imgsrc="cat" visit="'/about '" :btnName="'Get Started'"/>
  </div>
</template>

<script setup>
import TwoInOne from "../components/TwoInOne.vue";
import cat from "../assets/images/cat.jpg";
</script>

<style scoped></style>
