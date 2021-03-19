<template>
  <NuxtLink class="bg-blue-700 hover:bg-blue-600 text-white p-2 rounded" :to="to"><slot /></NuxtLink>
</template>

<script>
export default {
  props: ["to"]
}
</script>
