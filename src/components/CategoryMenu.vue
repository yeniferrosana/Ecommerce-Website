<template>
  <v-card color="#111111" height="150px" tile flat class="d-flex align-center justify-center" dark>
    <v-row>
      <v-col cols="12" sm="12">
        <h4 class="text-center">ZAPATOS PARA HOMBRE</h4>
      </v-col>
      <v-col cols="12" sm="12">
        <v-breadcrumbs :items="items" class="justify-center mt-n7" dark>
          <template v-slot:divider>
            <v-icon color="#e3e4e5">mdi-chevron-right</v-icon>
          </template>
        </v-breadcrumbs>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
  export default {
  
    data: () => ({
      items: [
      {
        text: "Inicio",
        disabled: false,
        href: "breadcrumbs_home"
      },
      {
        text: "Catálogo",
        disabled: false,
        href: "breadcrumbs_catalog"
      },
      {
        text: "Hombres",
        disabled: false,
        href: "breadcrumbs_men"
      },
      {
        text: "Zapatos",
        disabled: false,
        href: "breadcrumbs_shoes"
      }
    ],
    })
  }
</script>

<style scoped>

</style>
