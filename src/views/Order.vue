<template>
  <v-container
    fluid>
      <v-img
        src="https://marketplace.canva.com/EAEjbJ_CoDU/1/0/1600w/canva-black-brown-modern-cafe-logo-KU6mft9LBO0.jpg"
        max-height="200"
        class="mt-16"
        contain>
      </v-img>
      <div class="pa-5">
        <h3 class="pb-3">Beverages</h3>
          <v-row>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                FRAPPE
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                MILKTEA
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                YOGURT
              </v-btn>
            </v-col>
          </v-row>
      </div>
      <div class="pa-5">
        <h3 class="pb-3">Snacks/Meals</h3>
          <v-row>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                Pizza
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                Nachos
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                Burger
              </v-btn>
            </v-col>
          </v-row>
      </div>
      <div class="pa-5">
        <h3 class="pb-3">Promo/Mealset</h3>
          <v-row>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                Mealset
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                Buy 3
              </v-btn>
            </v-col>
            <v-col cols="4">
              <v-btn x-large dark color="warning">
                39ers
              </v-btn>
            </v-col>
          </v-row>
      </div>
  </v-container>
</template>

<style>
  .v-btn:not(.v-btn--round).v-size--x-large {
    height: 109px;
    min-width: 225px;
    padding: 0 23.1111111111px;
    font-size: 16pt;
    letter-spacing: 3px;
  }
</style>

    
<script>
  export default {
    name: 'Home'
  }
</script>
