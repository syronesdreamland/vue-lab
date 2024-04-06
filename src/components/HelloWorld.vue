<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    
    <h2>
      Alif Muhammad Aditya<br>
      <br>  
      <h3>Ini merupakan tugas portfolio untuk memenuhi tugas Prak PBK</h3>
    </h2>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
  padding: 5%;
}

h2 {
  font-weight: 500;
  font-size:180%;
  position: relative;
  top: -10px;
  color: white;
  padding: 5%;
}

h3 {
  font-size: 1rem;
  font-weight: 400;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
