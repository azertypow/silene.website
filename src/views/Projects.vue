<template>
  <div class="v-projects s-container">

    <img class="s-page-header" alt="Silène logo" src="../assets/silene-illu--1.jpg">

    <h1>actualité / projets</h1>

    <div class="s-page_content">

      <h2>Les Semailles</h2>
      <p>Fin 2020, les coopératives Ciguë et Silène ont obtenu ensemble un droit de superficie sur une parcelle du quartier des Semailles, au Grand-Lancy. Une nouvelle coopérative devra être fondée ainsi pour réunir les deux entités. La FPLC, propriétaire du terrain, est l'un des pilotes du projet, avec la ville de Lancy et le canton de Genève.  À cette fin, les investisseurs participent à l'organisation d'un concours d'urbanisme et d'architecture à deux degrés, qui vise à explorer de multiples scénarios et à choisir un projet exemplaire de qualité. En parallèle, les coopératives Ciguë et Silène organisent depuis début 2021 des ateliers de concertation pour imaginer un habitat convivial, écologique et sans voiture. Les ambitions des coopératives sont grandes en termes d’écologie et de mobilité ainsi qu’au sujet de la forme urbaine et de la qualité des espaces publics, tout en mettant en avant une démarche participative exemplaire.</p>
      <p>Les coopératives Ciguë et Silène, ainsi que la Fondation Immobilière de Droit Public Camille Martin (FCM), avec laquelle elles se sont associées pour ce projet, souhaitent défendre des hauts standards de qualité et porter la voix des coopérateurices dans ce processus. Leur objectif est de créer un bâtiment avec une forte mixité sociale et programmatique, mélangeant des appartements HBM, des appartements communautaires pour les étudiants et les post-étudiants, ainsi que des appartements pour personnes en formation avec enfants. Des espaces partagés au sein de l’immeuble sont souhaités pour l’ensemble des futur.x.e.s habitant.x.e.s. Les coopératives prévoient également la construction d'espaces communs et d'arcades ouvertes sur le quartier et souhaitent vivement participer à la vie du voisinage des Semailles.</p>
      <p>La coopérative Silène se réjouit de cette première expérience collaborative et attend avec joie et ferveur la réalisation de son premier immeuble, dans le quartier des Semailles !</p>

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
