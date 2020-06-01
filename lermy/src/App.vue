<template>
  <v-app>
    <Navbar />
    <Card />

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import Navbar from '@/components/Navbar'
import Card from '@/components/Card'

export default {
  name: 'App',

  components: {
    Navbar,
    Card,
  },

  data: () => ({
    //
  }),
};
</script>
