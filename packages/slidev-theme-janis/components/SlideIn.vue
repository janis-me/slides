<template>
  <span
    v-motion
    :initial="{
      opacity: 0,
      y: 10,
    }"
    :enter="{
      opacity: 1,
      y: 0,
    }"
    style="display: inline-block"
  >
    <slot />
  </span>
</template>
