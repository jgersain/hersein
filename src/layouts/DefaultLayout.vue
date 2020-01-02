<template>
  <div class="default-layout">
    This is default layout
    <header-partial></header-partial>
    <footer-partial></footer-partial>
  </div>
</template>

<script>
import HeaderPartial from '@/partials/HeaderPartial.vue';
import FooterPartial from '@/partials/FooterPartial.vue';

export default {
  name: 'DefaultLayout',
  components: {
    HeaderPartial,
    FooterPartial,
  },
};
</script>
