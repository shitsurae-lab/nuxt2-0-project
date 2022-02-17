<template>
  <div>
    <NuxtLogo />
    <Nav />
    <Nuxt />
  </div>
</template>
<script>
import NuxtLogo from '../components/NuxtLogo.vue'
import Nav from '../components/Nav.vue'
export default {
  data() {
    return {}
  },
  components: { NuxtLogo, Nav },
}
</script>
