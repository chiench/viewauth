<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="3" v-for="(img,i) in imgae" :key="i" > 
        <v-img
          :src="require(`../assets/${img.src}`)"
          class="my-3"
        />
      </v-col>
    </v-row>
    <v-divider/>
  </v-container>
  
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
        imgae:[
            {src:'client-vuejs.png'},
            {src:'client-logo-apache.png'},
            {src:'client-laravel.png'},
            {src:'client-oauth.png'},
        ],
    }),
  }
</script>
