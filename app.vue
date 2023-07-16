<script setup lang="ts">
useHead({
  htmlAttrs: { lang: () => 'ja', prefix: 'og: http://ogp.me/ns#' },
  meta: [
    { 'http-equiv': 'refresh', content: '' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1.0,maximum-scale=1.0' },
    { name: 'keywords', content: () => 'keywords' },
    { name: 'format-detection', content: 'telephone=no' },
    { name: 'theme-color', content: '#FFF' },
    { hid: 'robots', name: 'robots', content: 'noindex' },
  ],
  link: [],
  script: [],
  noscript: [{ children: 'JavaScript is required' }],
  title: '',
  bodyAttrs: {
    class: () => 'lang-ja',
  },
});
</script>
<template>
  <div class="px-6 pt-10">
    <v-container class="bg-white">
      <div class="">aaaaa</div>
      <div class="mt-3">
        <v-text-field label="Label"></v-text-field>
      </div>
      <div class="mt-3">
        <v-textarea label="Label"></v-textarea>
      </div>
      <div class="mt-3 d-flex">
        <v-btn variant="flat" color="primary" class="ms-auto">btn</v-btn>
      </div>
    </v-container>
  </div>
</template>

<style lang="scss" scoped></style>
