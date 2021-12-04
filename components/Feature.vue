<template>
  <div
    v-editable="blok"
    class="py-2 text-center">
    <a :href="blok.link">
    <img
      class="mx-auto"
      :src="blok.image.filename">
    <h1 class="text-lg">{{ blok.name }}</h1>
    <p class="text-gray-600">
      {{ blok.description }}
    </p>
    </a>
  </div>
</template>
 
<script>
export default {
  props: {
    blok: {
      type: Object,
      required: true
    }
  }
}
</script>