<template>
  <div class="v-contact s-container">
    <img class="s-page-header" alt="Silène logo" src="../assets/silene-illu--2.jpg">

    <h1>
      contact
    </h1>

    <div class="s-page_content">
      <h2>Pour devenir membre</h2>

      <p>Nous sommes à la recherche de nouvelles membres, si vous souhaitez plus d’informations et/ou que le projet vous
        intéresse, vous pouvez nous contacter par email à l’adresse suivante : <a href="mailto:silène.logement@gmail.com">silène.logement@gmail.com</a>.</p>


      <h2>Nous proposer un logement</h2>

      <p>En partenariat avec Silène, vous offrez la possibilité à des personnes dont le mode et/ou les conditions de vie
        ne permettent pas l’accès à des logements au prix du marché genevois d’être logées dignement. De cette façon,
        vous contribuez à l’engagement envers la cause du logement social et vous apportez une pierre à l’édifice d’un
        marché immobilier à prix abordables.</p>
      <p>En partenariat avec Silène par un contrat de bail, vous serez déchargé de la gestion locative et technique,
        endossée entièrement par Silène. De cette manière, votre bien immobilier sera utilisé avec soins et à bon
        escient. Votre logement aussi bien que la vie entourant ce lieu, resteront donc animés et permettront d’éviter
        la dégradation par l’abandon.</p>
      <p>Contactez-nous à <a href="mailto:silène.logement@gmail.com">silène.logement@gmail.com</a>.</p>

      <ended-page-info/>

    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import EndedPageInfo from "@/components/EndedPageInfo.vue"

export default defineComponent({
  name: 'Contact',
  components: {
    EndedPageInfo
  },
});
</script>

<style lang="scss" scoped>
.v-contact {

}
</style>
