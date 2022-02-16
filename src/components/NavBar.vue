<template>
  <v-app-bar 
    color="#3853D8" 
    dark
  >
    <v-btn icon>
      <v-icon> mdi-magnify </v-icon>
    </v-btn>
    <v-divider vertical class="ml-1 mr-3"></v-divider>
    <v-btn icon>
      <v-icon> mdi-menu </v-icon>
    </v-btn>
    <v-toolbar-title>
      <span class="caption">Seleccionar</span><br>Categoría
    </v-toolbar-title>
    <v-vertical class="ml-5"></v-vertical>
    <div class="title-nav">

    </div>
  </v-app-bar>
</template>

<script>
export default {

}
</script>

<style scoped>
.title-nav {
  position: absolute;
  margin-left: auto;
  margin-right: auto;
  left: 0;
  right: 0;
  text-align: center;
}
</style>