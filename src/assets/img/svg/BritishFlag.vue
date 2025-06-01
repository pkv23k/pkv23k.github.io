<template>
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
    <circle cx="50" cy="50" r="50" fill="#012169" />
    <clipPath id="circleClip">
      <circle cx="50" cy="50" r="50" />
    </clipPath>
    <polygon
      points="0,0 20,0 50,35 80,0 100,0 100,20 65,50 100,80 100,100 80,100 50,65 20,100 0,100 0,80 35,50 0,20"
      fill="#FFFFFF"
      clip-path="url(#circleClip)"
    />
    <polygon
      points="0,0 12,0 50,32 88,0 100,0 100,12 68,50 100,88 100,100 88,100 50,68 12,100 0,100 0,88 32,50 0,12"
      fill="#C8102E"
      clip-path="url(#circleClip)"
    />
    <rect x="40" y="0" width="20" height="100" fill="#FFFFFF" clip-path="url(#circleClip)" />
    <rect x="0" y="40" width="100" height="20" fill="#FFFFFF" clip-path="url(#circleClip)" />
    <rect x="45" y="0" width="10" height="100" fill="#C8102E" clip-path="url(#circleClip)" />
    <rect x="0" y="45" width="100" height="10" fill="#C8102E" clip-path="url(#circleClip)" />
  </svg>
</template>

<style lang="scss" scoped>
svg {
  width: 2.8125rem;
  height: 2.8125rem;
}
</style>
