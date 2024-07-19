<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Corporis corrupti voluptate consequatur beatae dolor debitis maiores veritatis dolores aperiam ullam, facere, expedita, aliquam sit enim. Labore dolores deleniti voluptates obcaecati.</p>
  </div>
</template>

<script setup>
  const { id } = useRoute().params
</script>

<style lang="scss" scoped></style>