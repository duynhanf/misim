<script setup>
const route = useRoute()

definePageMeta({
  validate: async (route) => {
    // Check if the id is made up of digits
    return /^\d+$/.test(route.params.id)
  },
})
</script>

<template>
  <div>
    <h1>
      Post #{{ route.params.id }}
    </h1>
  </div>
</template>
