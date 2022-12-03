<script setup>
import { useCounterStore } from "../stores/counter"; 
import MSLogin from "../components/common/MSLogin.vue"

const store = useCounterStore();
</script>

<template>
  <div class="about">
    <MSLogin></MSLogin>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
