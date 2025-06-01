<template>
  <svg viewBox="0 0 50 100" xmlns="http://www.w3.org/2000/svg">
    <polyline points="0,0 45,50 0,100" stroke-width="10" fill="none" />
  </svg>
</template>

<style lang="scss" scoped>
svg {
  stroke: map.get(vars.$colors, 'c-white', 'primary');
  width: 1.25rem;
  height: 1.25rem;
}
</style>
