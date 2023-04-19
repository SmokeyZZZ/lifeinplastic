<template>
   <v-card
  
    max-width="344"
  >
    <v-img
    src="../../img/logo.png"
      height="200px"
      cover
    ></v-img>

    <v-card-title>
     {{ title }}
    </v-card-title>

    <v-card-subtitle>
      {{ authors }}
    </v-card-subtitle>
  </v-card>
  
</template>

<script setup >
const props = defineProps({
  title: String,
  authors:String,
  imgUrl:String,
})

</script>

<style scoped>

</style>