<template>
  <div class="v-projects s-container">

    <img class="s-page-header" alt="Silène logo" src="../assets/silene-illu--1.jpg">

    <h1>actualité / projets</h1>

    <div class="s-page_content">

      <h2>Les Semailles?</h2>

      <ended-page-info/>

    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import EndedPageInfo from "@/components/EndedPageInfo.vue"

export default defineComponent({
  name: 'Projects',
  components: {
    EndedPageInfo
  },
});
</script>

<style lang="scss" scoped>
.v-projects {

}
</style>
