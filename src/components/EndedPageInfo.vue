<template>
  <div class="v-ended-page-info">
    <h6>*Le contenu de ce site est inclusif et indépendant de toute assignation et/ou identité de genre. L’usage de la forme
      contractée est privilégiée quand elle est possible, sinon, le féminin est employé comme genre neutre/générique
      pour but d’alléger le texte et d’en faciliter la lecture, sans aucune intention discriminatoire.</h6>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'EndedPageInfo',
  components: {
  },
});
</script>

<style lang="scss" scoped>
.v-ended-page-info {
  line-height: 1em;
}
</style>
