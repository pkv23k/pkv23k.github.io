<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <circle cx="50" cy="50" r="50" fill="#c60b1e" />
    <clipPath id="circleClip">
      <circle cx="50" cy="50" r="50" />
    </clipPath>
    <rect x="0" y="33.33" width="100" height="33.33" fill="#ffc400" clip-path="url(#circleClip)" />
    <rect x="0" y="0" width="100" height="33.33" fill="#c60b1e" clip-path="url(#circleClip)" />
    <rect x="0" y="66.66" width="100" height="33.33" fill="#c60b1e" clip-path="url(#circleClip)" />
  </svg>
</template>

<style lang="scss" scoped>
svg {
  width: 2.8125rem;
  height: 2.8125rem;
}
</style>
