<template lang="pug">
.flex.w-full.p-2.text-sm.border-b-2(class="bg-zinc-200 border-zinc-300 dark:bg-zinc-800 dark:border-white/5")
  BaseButton(to="/")
    | Rim
  BaseButton(to="/docs")
    | Docs
  BaseButton(to="/about")
    | About
  BaseButton(to="/blog")
    | Blog
  BaseButton.ml-auto(to="/login")
    | Login
</template>
