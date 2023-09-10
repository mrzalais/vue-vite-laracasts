<template>
  <div>
    <h5>{{ state.name }}</h5>

    <button @click="state.name = 'New name'" class="btn btn-primary">Change name</button>

    <ul>
      <li><a href="#">Get a job</a></li>
      <li><a href="#">Contact us</a></li>
    </ul>
  </div>
</template>

<script setup>
import { state } from '@/stores/quizStore.js'
</script>