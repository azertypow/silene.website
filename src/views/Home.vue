<template>
  <div class="v-home s-container">
    <img class="s-page-header" alt="Silène logo" src="../assets/silene-illu--3.jpg">

    <h1>
      nous
    </h1>

    <div class="s-page_content">

      <h2>La Coopérative Silène</h2>

      <p>Silène est une primo-coopérative d’habitantes née du souhait d’anciennes et actuelles coopératrices Ciguë et
        jeunes professionnelles, de prolonger l’expérience de la colocation au-delà des études. Une des difficultés des
        personnes en formation notamment lorsqu’elles quittent leur colocation étudiante est de faire face à l’isolement
        dans des appartements au-dessus de leurs moyens, dans un mode de vie contraint. Au-delà de la formation, il
        existe un réel besoin pour les personnes ne souhaitant pas ou n’ayant pas la possibilité d’entrer dans la
        logique hyperactive actuelle qui leur demande de posséder un travail stable et à plein temps afin de pouvoir
        vivre dans un logement convenable.</p>

      <p>C’est pourquoi Silène souhaite devenir un tremplin pour pallier la difficulté des personnes précaires et
        précarisées qui se trouvent plongées dans le circuit d’un marché libre sans concessions. Le logement
        communautaire en coopérative permet non seulement l’accès à des prix abordables mais aussi à la création d’un
        lien solidaire. Pour cela Silène participe à des appels à projet pour des logements pérennes et a obtenu de la
        FPLC en collaboration avec la Ciguë et la Fondation Camille-Martin un terrain lui offrant 25 logements dans le
        quartier des Semailles. Parallèlement à cela, Silène est à la recherche de logement temporaire pour lutter
        contre les logements vides.</p>

      <p>Intrinsèquement participative, Silène est constituée de futures habitantes prêtes à s’investir pleinement dans
        le développement et l’exploitation de leur habitat. Ceci afin de bâtir une structure qui adopte un mode de vie
        collectif, participatif, inclusif et écologique pour vivre la ville à travers un prisme solidaire.</p>


      <h2>Objectifs</h2>

      <p>Silène souhaite loger des personnes ayant des difficultés à s’insérer sur le marché immobilier ordinaire et
        offrir à ces personnes de peu de moyens l’opportunité de vivre dans des logements dignes. Pour Silène
        l’expérience d’un logement digne se caractérise par un lieu de qualité et à prix abordable où il est possible de
        créer des liens, d’adopter un mode de vie collectif, participatif, inclusif, écologique et communautaire pour
        vivre la ville de façon solidaire. De plus, Silène souhaite offrir à ses coopératrices une ouverture à
        l’extérieur en favorisant la vie de quartier, la collaboration avec d’autres coopératives de logement et un lien
        avec la ville.</p>


      <h2>Les coopératrices</h2>

      <p>La coopérative est ouverte à toute personne en accord avec la vision de Silène et qui souhaite s’investir dans
        un projet communautaire et participatif de façon inclusive et respectueuse à l’environnement. Les conditions à
        respecter sont principalement le critère de revenu et fortune établi par l’État en fonction du RDU.</p>

      <ended-page-info/>

    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import EndedPageInfo from "@/components/EndedPageInfo.vue"

export default defineComponent({
  name: 'Home',
  components: {
    EndedPageInfo
  },
});
</script>

<style scoped lang="scss">

</style>
