<template>
    <v-app-bar :elevation="2" color = "black">
      <v-app-bar-title>FAHARI JERSEY STORES</v-app-bar-title>
      <v-btn to="/" primary >Home</v-btn>
      <v-btn to="/products">Products</v-btn>
      <v-btn to="/aboutus">About Us</v-btn>
      <v-btn to="/contactus">Contact Us</v-btn>
      <v-btn to="/cart">cart</v-btn>
      <v-badge color="white" :content="cart.length">
        <v-icon>mdi-store-outline</v-icon>
      </v-badge>
       </v-app-bar>
  </template>
  <script>
import {mapGetters } from 'vuex'

export default {
  computed: {
            ...mapGetters({
                cart: 'cart'
            })
        },
}
  </script>