<template>
  <v-app>
    <Header/>

    <v-content>
      <nuxt/>
    </v-content>

    <Footer />

    <loader></loader>
  </v-app>
</template>

<script>
  import Header from '~/components/Header.vue'
  import Footer from '~/components/Footer.vue'
  import Loader from '~/components/Loader'

  export default {
    components: {Loader, Header, Footer}
  }
</script>
