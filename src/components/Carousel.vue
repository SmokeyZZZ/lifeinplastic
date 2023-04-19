<template>
    <v-carousel class="carousel"
    v-bind:cycle="true"
    show-arrows="hover"
   hide-delimiter-background
   color="white"
    
    
    >
        <v-carousel-item
          src="img/backgroundprova.jpg"
          cover
        ></v-carousel-item>
      
        <v-carousel-item
          src="img/bottiglie.jpg"
          cover
        ></v-carousel-item>
      
        <v-carousel-item
          src="img/tappi.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
  </template>
  <style>
  .v-carousel
  {
    
    max-width: 800px;
    height: auto;
    border-radius: 5%;
  }
  
</style>
