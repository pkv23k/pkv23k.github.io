<template>
  <svg viewBox="0 0 100 50" xmlns="http://www.w3.org/2000/svg">
    <polyline points="0,0 50,45 100,0" stroke-width="10" fill="none" />
  </svg>
</template>

<style lang="scss" scoped>
svg {
  stroke: map.get(vars.$colors, 'c-white', 'primary');
  margin: 0 0 0 0.5rem;
  width: 1.25rem;
  height: 1.25rem;
}
</style>
