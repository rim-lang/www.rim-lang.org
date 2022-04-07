<template lang="pug">
div
  h1(v-if="error.statusCode === 404") Page not found
  h1(v-else="") An error occurred
  nuxtlink(to="/") Home page
</template>

<script>
export default {
  props: ['error'],
  layout: 'error', // you can set a custom layout for the error page
}
</script>
