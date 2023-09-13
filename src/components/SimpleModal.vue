<script setup>
  defineProps({
    show: Boolean
  })
</script>

<template>
  <div v-if="show" class="modal-mask">
    <div class="modal-container">
      <header>header text</header>

      <div>main text</div>

      <footer>footer text</footer>
    </div>
  </div>
</template>

<style>
.modal-mask {
  position: fixed;
  inset: 0;
  background-color: rgba(0, 0, 0, .6);
  display: grid;
  place-items: center;
}

.modal-container {
  background: white;
  padding: 1rem;
  width: 80vw;
  max-width: 500px;
}
</style>