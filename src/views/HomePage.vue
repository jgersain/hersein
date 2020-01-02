<template>
  <div>
    This is home page
    <default-layout></default-layout>
  </div>
</template>

<script>
import DefaultLayout from '@/layouts/DefaultLayout.vue';

export default {
  name: 'HomePage',
  components: {
    DefaultLayout,
  },
};
</script>
