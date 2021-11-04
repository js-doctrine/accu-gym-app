<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
<div class="container">
        <img width="351" height="415" class="girl" src="../assets/girl.png">
        <p class="smarter"> Now Gym Smarter with AccuGym</p>
        <p class="fitness"> An AI based fitness app that can change your life </p> 
        <button class="get"> Get started </button>
    </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  background: #20202c;
  min-height: 100vh;
  padding: 0px 35px;
}
.Height {
  margin: auto;
  position: absolute;
  width: 327px;
  height: 56px;
  left: 24px;
  top: 200px;

  background: #343447;
  border-radius: 30px;
}
.fitness {
  font-family: Manrope;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
  margin: 0;
  color: #8a8fa8;
}
.get {
  background-color: transparent;
  background: linear-gradient(80.52deg, #7959f4 42.3%, #e37af6 119.33%);
  border-radius: 30px;
  border: none;
  outline: none;
  font-family: Manrope;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
  text-align: center;
  color: #ffffff;
  padding: 19px 65px;
  width: fit-content;
  margin: 57px auto;
}
.girl {
  display: block;
  margin: 0 auto;
  }
</style>
