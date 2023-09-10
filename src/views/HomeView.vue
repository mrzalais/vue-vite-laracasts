<script setup>
import Quiz from '@/components/Quiz/QuizBase.vue'
</script>

<template>
  <main>
    <Quiz :quiz="{ name: 'My first quiz', questions: []}"/>
  </main>
</template>
