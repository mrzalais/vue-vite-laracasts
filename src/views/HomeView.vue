<script setup>
import Quiz from '@/components/Quiz/QuizBase.vue'
import { state } from '@/stores/QuizStore'
</script>

<template>
  <main>
    <Quiz :quiz="state"/>
  </main>
</template>
