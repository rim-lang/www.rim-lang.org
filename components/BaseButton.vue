<template lang="pug">
nuxt-link(:to="to" :class="cclass" v-if="to")
  slot
button(v-else="")
  slot
</template>

<script>
export default {
  props: {
    to: String,
    cclass: String,
  },
}
</script>
