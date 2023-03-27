<template>
  <v-card class="elevation-4 my-auto mb-4">
    <v-img :src="image" aspect-ratio="1.7"></v-img>
    <v-card-title>{{ title }}</v-card-title>
    <v-card-text>{{ text }}</v-card-text>
    <v-card-actions class="justify-end">
      <v-btn color="#90a4ae" text-color="yellow" @click="buttonClick">Click me</v-btn>
    </v-card-actions>
  </v-card>
</template>

  
<script>
  export default {
    props: {
      image: String,
      title: String,
      text: String,
    },
    methods: {
      buttonClick() {
        this.$emit("button-click");
      },
    },
  };
</script>


  