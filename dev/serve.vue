<script>
import Vue from 'vue';
import VuetifyFormBaseSsr from '@/vuetify-form-base-ssr.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VuetifyFormBaseSsr
  }
});
</script>

<template>
  <div id="app">
    <vuetify-form-base-ssr />
  </div>
</template>
