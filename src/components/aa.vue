<template>
  <div>
    <body class="font-body text-body">
      <p class="font-sans text-lg">dsfhdslkfdksfldl</p>
      <p class="text-green-200">12</p>
      <p class="font-mono text-lg">Hello world</p>
      <p class="text-yellow-600">12</p>
      <p class="font-mono text-orange-400">{{ message }}</p>
    </body>
  </div>
</template>

<script>
export default {
  name: 'aa',
  props: ["img", "imgAlt", "eyebrow", "title", "pricing", "url", 'message']
};
</script>