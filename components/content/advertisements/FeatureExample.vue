<script setup>
const item = computed(() => ({
  title: "My Awesome Note App",
  description: "This note app is a great way to do edit texts and organize things like you have never seen before.",
  featured: true,
}));
</script>


<template>
  <DirectoryItem class="block w-96 h-42 my-8" :item="item" />
</template>