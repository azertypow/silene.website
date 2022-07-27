<template>
  <div class="v-footer-app">
    <img class="v-footer-app__logo" alt="logo silene"  src="../assets/logo-silene.jpg">
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'FooterApp',
  components: {
  },
});
</script>

<style lang="scss" scoped>
@import "../style/main";

.v-footer-app {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  box-shadow: var(--site-color) 0 0 20px 10px;
  background: var(--site-color);
}

.v-footer-app__logo {
  width: 60px;
  display: block;
  padding-left:   var(--gutter);
  padding-top:    calc( var(--gutter) / 2 );
  padding-bottom: calc( var(--gutter) / 2 );
}
</style>
