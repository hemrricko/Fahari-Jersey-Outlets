<script>
export default {
  data() {
      return {
        image: "/images/vinicius-amnx-amano-dbOV1qSiL-c-unsplash (1).jpg",
        message: "Hello World!",
        product: 'Sweets',
        url: 'https://www.vuejs.org/',
        //simple array demo
        stock: ["Sweets", "Lollipop", "Chocolate"],
        //Object demo
        stockDetails : [
            {
                itemNumber: 1,   
                itemName : "Sweets",
                itemPrice : 5,
                itemQuantity : 30,
                itemImage: '/images/customerbox-aXq1oCCjlVM-unsplash.jpg'
            },
            {
                itemNumber: 27466,
                itemName : "Lollipop",
                itemPrice : 10,
                itemQuantity : 4,
                itemImage: '/images/jamie-albright-AHF_ZktTL6Q-unsplash (1).jpg'
            },
            {
              itemNumber: 232,
                itemName : "Chocolate",
                itemPrice : 120,
                itemQuantity : 50,
                itemImage: '/images/tetiana-bykovets-TzN2odwnesg-unsplash.jpg'
            }
        ],
        totalStock: 100
      }
    },

    methods() {
      //we shall add our functions here
    },

    computed(){
      //we use this when working with forms
    }
}
</script>


<template>

  <v-card
    class="mx-auto"
    width="1000"
  >
    <v-carousel>
        <v-carousel-item
            src="public/images/download.jpg"
            cover
        ></v-carousel-item>

        <v-carousel-item
          src="public/images/2024 Brazil Special Edition Goddess Soccer Jersey.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="public/images/Adidas Germany Home Junior Short Sleeve Jersey 2022 Colour_ White, Size_ 11-12 years.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="public/images/Brazil Nike Home short sleeve jersey - L.jpg"
          cover
        ></v-carousel-item>

        <v-carousel-item
          src="public/images/Inter Miami Jersey _ Color_ Black _ Size_ Various.jpg"
          cover
        ></v-carousel-item>
      </v-carousel>
  </v-card>
  <v-spacer></v-spacer>
  
  <v-card align="center">
    <v-card-item>
      <v-card-title>Best Sportswear in town!</v-card-title>
      <v-card-subtitle>Amaizing shop that'll cater for all your jersey needs! </v-card-subtitle>
      </v-card-item>
      <v-card-text>
        Join us in celebrating the spirit of sports and wear your pride with Fahari Outlet Stores! Thank you for choosing us as your go-to jersey provider.
    </v-card-text>
  </v-card>

      <v-divider></v-divider>
      <v-divider></v-divider>
      <v-divider></v-divider>
  <h3 class="text-center">Customer Reviews</h3>
  <v-divider></v-divider>

  
    <v-col cols="12" md="6">
      <v-card align="centre"
        subtitle="Daniella Apunga"
        text="I will be recommending my friends"
        title="10/10"
      ></v-card>
    </v-col>

    <v-col cols="12" md="6">
      <v-card>
        <template v-slot:title>
          Impressive customer service
        </template>
        <template v-slot:subtitle>
          You will see me again
        </template>
        <template v-slot:text>
          10/10
        </template>
      </v-card>
    </v-col>
    
    <v-col cols="12" md="6">
      <v-card>
        <v-card-item>
          <v-card-title>Wonderful Products</v-card-title>
          <v-card-subtitle>High class quality</v-card-subtitle>
        </v-card-item>
        <v-card-text>
          I would highly recommend
        </v-card-text>
      </v-card>
    </v-col>

</template>