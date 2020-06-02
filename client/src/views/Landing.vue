<template>
  <div name="wrapper">
    <v-row>
      <v-app-bar 
        app
        absolute
        hide-on-scroll
        prominent
        color="#45443e">

      <v-toolbar-title id="title_logo">Re.verie</v-toolbar-title>

      <v-spacer></v-spacer>

      <div class="">
      <v-btn class="" small rounded color="#F3F348">Login</v-btn> 
      </div>
      <div class="kacke will nicht auseinander"></div>
      <v-btn class="" small outlined rounded color="#F3F348">SignUp</v-btn>
    </v-app-bar>
    </v-row> 

    <v-btn>hallo</v-btn>

    <template>
    <v-footer
    color="primary lighten-1"
    padless
    app
  >
    <v-row justify="center" no-gutters>
      
      <v-btn color="#f3f348" text rounded class="my-2">hello</v-btn>
      <v-col class="primary lighten-2 py-4 text-center white--text" cols="12">
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-row>
  </v-footer>
    </template>
  </div>
</template>

<script>
export default {
  name: "Landing"
}
</script>

<style>

  .wrapper {
    background-color: #7c7c77;
  }

  #title_logo {
    color: #f3f348;
    font-family: "Lucida Console", Courier, monospace;
    font-size: 40px;
  }
</style>
