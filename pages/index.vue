<template>
  <Index></Index>
</template>

<script lang="ts">
import Vue from 'vue'
import Index from "~/components/arsanandha/Index.vue";

export default Vue.extend({
  head:{
    title: 'arsanandha.xyz',
    meta: [
      { charset: 'utf-8'},
      { name: 'viewport', content: 'width=device-width, initial-scale=1'},
      {
        hid: 'arsanandha.xyz',
        name: 'arsanandha.xyz',
        content: 'arsanandha.xyz'
      },
      { property: "og:site_name", content: "arsanandha.xyz" },
      { hid: "og:type", property: "og:type", content: "website" },
      {
        hid: "og:url",
        property: "og:url",
        content: "https://inthanon.arsanandha.xyz",
      },
      {
        hid: "og:title",
        property: "og:title",
        content: "Inthanon (behalf of arsanandha.xyz)",
      },
      {
        hid: "og:description",
        property: "og:description",
        content: "Inthanon is highest mountain in Thailand.",
      },
      {
        hid: "og:image",
        property: "og:image",
        content: "https://images.unsplash.com/photo-1512553353614-82a7370096dc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1332&q=80",
      },
      { property: "og:image:width", content: "640" },
      { property: "og:image:height", content: "360" },
    ]
  },
  components: {Index}
})
</script>
