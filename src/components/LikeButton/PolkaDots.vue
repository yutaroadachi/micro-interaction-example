<template>
  <span class="PolkaDots"></span>
</template>

<style scoped>
.PolkaDots {
  position: absolute;
  top: 0;
  left: 0;
  width: 36px;
  height: 36px;
  background-color: transparent;
  border: 2px dotted #f91880;
  border-radius: 50%;
  opacity: 0%;
  animation-name: scale-and-fade;
  animation-duration: 1s;
}

@keyframes scale-and-fade {
  0% {
    opacity: 100%;
  }
  100% {
    transform: scale(150%);
  }
}
</style>
