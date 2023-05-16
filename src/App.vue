<template>
  <QuillEditor content-type="html" v-model:content="teste" />
  <div v-html="teste"></div>
</template>

<script setup lang="ts">
import { QuillEditor } from "@vueup/vue-quill";
import "@vueup/vue-quill/dist/vue-quill.snow.css";
import { ref } from "vue";

const teste = ref("");
</script>

<style scoped></style>
