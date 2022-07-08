<template lang="pug">
nuxt-link(:to="to" v-if="to")
  slot
button(v-else="")
  slot
</template>

<script>
export default {
  props: {
    to: String,
  },
}
</script>
