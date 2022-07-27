<template>
  <div class="v-app">
    <header class="v-app-header">
      <div class="v-app-header__logo" ><router-link to="/">Silène</router-link></div>

      <nav class="v-app-header__nav">
        <router-link to="./" >nous</router-link>
        <router-link to="./projects" >actualité&nbsp;/&nbsp;projets</router-link>
        <router-link to="./contact" >contact</router-link>
      </nav>
    </header>

    <main class="v-app-main">
      <Transition name="fade">
        <router-view/>
      </Transition>
    </main>

    <footer-app/>
  </div>

</template>

<style lang="scss">
@import "style/main";

.v-app {
  padding: 60px var(--gutter);
}

.v-app-header {
  background-color: var(--site-color);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  box-sizing: border-box;
  padding: var(--gutter);
  z-index: 100000;
  display: flex;
  justify-content: space-between;
  //border-bottom: solid 2px;
  box-shadow: var(--site-color) 0 0 20px 10px;
}

.v-app-header__logo {
  font-weight: bold;
  > * {
    text-decoration: none;
  }
}

.v-app-header__nav {
  margin-right: 0;

  > * {
    margin-left: var(--gutter);
    color: inherit;
    text-decoration: none;

    .router-link-exact-active {
      text-decoration: underline;
    }
  }
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
<script>
import FooterApp from "@/components/FooterApp.vue"
export default {
  components: {FooterApp},
}
</script>
