<template>
  <div>
    <p>Blogs details {{ id }}</p>
  </div>
  <p>isi blog nya </p>
</template>

<script setup>
    const { id } = useRoute().params
</script>

<style>

</style>