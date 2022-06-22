<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup>
useHead({
  title: "Contract App",
  viewport: "width=device-width, initial-scale=1, maximum-scale=1",
  charset: "utf-8",
  link: {
    rel: "stylesheet",
    href: "https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css",
    integrity:
      "sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==",
    crossorigin: "anonymous",
    referrerpolicy: "no-referrer",
  },
});
</script>
