<template>
  <v-app>
    <v-main>
      <Navbar
        titleStr="Demo App" :links="links" qrExp=""
      />
    </v-main>
  </v-app>
</template>

<script>
import Navbar from '../../src/components/Navbar.vue'
export default {
  components: {Navbar},
    data: () => ({
    links: [
      { icon: '', text: 'Home', route: '/'},
    ]
  }),

}
  //
</script>
