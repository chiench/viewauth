<template>
  <v-app>
    <!-- app de giu cho bar o dau  -->
    <v-app-bar
    app
    height="102"
    class="bg-white"
    >
      <div class="d-flex align-center">
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <InfoComponent/>
      <ImgaeComponent/>
      <ServiceComponet/>
    </v-main>
    <v-divider/>
    <FooterComponent/>

  </v-app>
</template>

<script>
import InfoComponent from './components/InfoComponent';
import ImgaeComponent from './components/ImgaeComponent';
import ServiceComponet from './components/ServiceComponet';
import FooterComponent from './components/FooterComponent';

export default {
  name: 'App',

  components: {
    InfoComponent,
    ImgaeComponent,
    ServiceComponet,
    FooterComponent,
  },

  data: () => ({
    //
  }),
};
</script>
<style scoped>
.app-bar{
  background-color: #ffffff;
}
</style>
