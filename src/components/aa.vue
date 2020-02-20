<template>
  <div>
    <img class="rounded" :src="img" :alt="imgAlt" />
    <div class="mt-2">
      <div>
        <div class="text-xs text-gray-600 uppercase font-bold">{{ eyebrow }}</div>
        <div class="font-bold text-gray-700 leading-snug">
          <a :href="url" class="hover:underline">{{ title }}</a>
        </div>
        <div class="mt-2 text-sm text-gray-600">{{ pricing }}</div>
      </div>
    </div>
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'aa',
  props: ["img", "imgAlt", "eyebrow", "title", "pricing", "url", 'message']
};
</script>