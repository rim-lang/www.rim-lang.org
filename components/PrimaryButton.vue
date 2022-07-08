<template lang="pug">
BaseButton.py-3.px-5.rounded-lg.border-1.border-teal-600.bg-teal-500(:to="to")
  slot
</template>

<script>
export default {
  props: {
    to: String,
  },
}
</script>
