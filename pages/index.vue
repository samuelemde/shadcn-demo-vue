<script setup lang="ts">
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
  <div class="flex min-h-screen flex-col">
    <div class="flex justify-end">
      <ThemeToggle />
    </div>
    <main class="flex flex-1 flex-col items-center justify-center gap-10">
      <h1 class="text-5xl font-black">Shadcn/UI Demo Vue</h1>
      <p class="max-w-96">
        Start adding components by either copy/pasting the code from the docs or
        by using the shadcn cli.
      </p>
      <Button size="xl">
        <a
          href="https://www.shadcn-vue.com/docs/introduction.html"
          target="_blank"
          rel="noopener noreferrer"
        >
          Read the Docs 📚
        </a>
      </Button>
    </main>
  </div>
</template>
