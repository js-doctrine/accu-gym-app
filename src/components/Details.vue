<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <div class="container"> 
    <div class="topline">
        <button class="Arrow"> <img src="Arrow.svg" alt="">
        </button>
            <p class="details-heading"> Personal Details</p>
    </div>
        <form class="run" Height="test" method="post" action="input1.php">
            <p class="heading"> Fill the details below to check your fitness index</p>
            <input class="read " type="text" size="40" placeholder="Height">
            <input class="read "  type="text" size="40" placeholder="Weight">
            <input class="read "  type="text" size="40" placeholder="Gender">
            <input class="read " type="text" size="40" placeholder="Age">
            <br>
            <button class="Submit"> Submit</button>
        </form>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  padding: 0px 24px;
}
@media (min-width: 768px) {
  .container {
    margin: 0 auto;
    max-width: 720px;
  }
}
@media (min-width: 576px) {
  .container {
    margin: 0 auto;
    max-width: 540px;
  }
}
@media (min-width: 992px) {
  .container {
    margin: 0 auto;
    max-width: 960px;
  }
}
@media (min-width: 1200px) {
  .container {
    margin: 0 auto;
    max-width: 1140px;
  }
}
.topline {
  display: flex;
}
.Arrow {
  border: none;
  outline: none;
  background: transparent;
}
.details-heading {
  font-family: Manrope;
  font-style: normal;
  font-weight: bold;
  font-size: 28px;
  line-height: 38px;
  letter-spacing: -0.02em;

  color: #ffffff;
}
.heading {
  font-family: Manrope;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;

  color: #8a8fa8;
}

.read:focus {
  border: 2px solid rgb(200, 87, 253);
}

.read {
  margin-bottom: 18px;
  padding: 17px 24px;
  border: none;
  outline: none;
  font-family: Manrope;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  /* identical to box height */
  color: #8a8fa8;
  background: #343447;
  border-radius: 30px;
  border: 2px solid transparent;
  width: 100%;
}
.Submit {
  display: block;
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
.run {
  width: 100%;
  max-width: 327px;
}
</style>
