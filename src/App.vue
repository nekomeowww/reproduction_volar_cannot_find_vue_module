<script setup lang="ts">
import C1 from './C1.vue'
import ComponentC1 from './components/C1.vue'
import ComponentDotC1 from '../dot/C1.vue'
import ComponentDotWithDotC1 from '../.dot/C1.vue'
</script>

<template>
  <C1 />
  <ComponentC1 />
  <ComponentDotC1 />
  <ComponentDotWithDotC1 />
</template>
