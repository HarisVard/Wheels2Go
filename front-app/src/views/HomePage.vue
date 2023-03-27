<template>
    <div>
      <!-- Your homepage content goes here -->
      <h1>This is an home page</h1>
      <v-container>
      <v-row>
        <v-col cols="12" sm="6" md="4" lg="3">
          <custom-card
            :image="image"
            :title="title"
            :text="text"
            @button-click="handleButtonClick"
          ></custom-card>
        </v-col>
      </v-row>
    </v-container>
    </div>
  </template>
  
  
  <script>
  import CustomCard from "@/components/CustomCard.vue";
  
  export default {
    components: {
      CustomCard,
    },
    data() {
      return {
        image: "./assets/images/",
        title: "Card Title",
        text: "Some description text for the card.",
      };
    },
    methods: {
      handleButtonClick() {
        console.log("Button clicked");
        // Perform your desired action here
      },
    },
  };
  </script>
  
<style>
  /* Your homepage CSS styles go here */
</style>
  