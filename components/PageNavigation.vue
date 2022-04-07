<template lang="pug">
.flex.w-full.p-2.text-sm.text-gray-800.border-b-2
  nuxt-link.py-2.px-4.border.border-gray-400.rounded.bg-gray-300(to="/" class="hover:bg-gray-300")
    | Rim
  nuxt-link.py-2.px-4.border.border-gray-400.rounded.bg-gray-300(to="/docs" class="hover:bg-gray-300")
    | Docs
  nuxt-link.py-2.px-4.border.border-gray-400.rounded.bg-gray-300(to="/about" class="hover:bg-gray-300")
    | About
  nuxt-link.py-2.px-4.border.border-gray-400.rounded.bg-gray-300(to="/blog" class="hover:bg-gray-300")
    | Blog
  nuxt-link.ml-auto.py-2.px-4.border.border-gray-400.rounded.bg-gray-300(to="/login" class="hover:bg-gray-300")
    | Login
</template>
