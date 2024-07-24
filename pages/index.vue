<script setup lang="ts">
import { Button } from '@/components/ui/button'

useHead({
  title: "Shadcn/UI Demo Vue",
  meta: [
    {
      name: "description",
      content: "Demo app to demo shadcn/ui",
    },
  ],
  link: [
    {
      rel: "icon",
      href: "/favicon.ico",
    },
  ],
});
</script>

<template>
  <main class="flex min-h-screen flex-col items-center justify-center gap-10 text-black">
    <h1 class="text-5xl font-black">Shadcn/UI Demo Vue</h1>
    <p class="max-w-96">
      Start adding components by either copy/pasting the code from the docs or by using the shadcn cli.
    </p>
    <Button><a
        href="https://www.shadcn-vue.com/docs/introduction.html"
        target="_blank"
    >
      Read the docs
    </a></Button>
  </main>
</template>
