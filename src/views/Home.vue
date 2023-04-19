<template>
  <div class="section">
      
      <v-container   
      >
          
          <v-row align="center"
          class="content"
          justify="center">
             
          <v-col class="slogan">
              <h1>LIFE IN <span class="highlighted">PLASTIC</span></h1>
              <h1>ISN'T<span class="highlighted"> FANTASTIC</span></h1>
          </v-col>
          <v-col><Carousel/></v-col>
         </v-row>
        </v-container>
  </div>
  </template>
  <style>
  *{list-style-type: none;}
  .section{
  /*background: url(img/bottiglie.jpg);*/
  background-repeat: no-repeat;
  background-size:cover;
  height: 100%;
  background-color:#90CAF9;
  }
  .content{
      font-size:3rem;
      font-weight: bold;
      text-align:center;
  }
  .content  
  {
   

   padding:149px;
  }
  .slogan
  {
      margin-right:100px;
      
      font-size: 50px;
  }
  .highlighted
  {
      color:white;
  }
  
  </style>
  <script >
  import Carousel from '../components/Carousel.vue';
  import Prodotto from '../components/Prodotto.vue';
  
  export default
  {
      components: 
      {
          Carousel,Prodotto,
      },
      data() {
          return {
             items:["cacca","pupu"] 
          }
      },
  }
  
  </script>
  
  
  