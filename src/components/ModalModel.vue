<template>
  <div class="modal-model">
    <div class="modal-model__inside"></div>
    <slot name="modalContent"></slot>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped>
.modal-model {
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background-color: rgba(0, 0, 0, 0.6);
  &__inside {
    position: fixed;
    max-width: 100vw;
  }
}
</style>
