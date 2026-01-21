<template>
  <div class="app-layout">
    <AppHeader />
    <slot />
  </div>
</template>

<script>
import AppHeader from './AppHeader.vue';

export default {
  name: 'AppLayout',
  components: {
    AppHeader,
  },
};
</script>
