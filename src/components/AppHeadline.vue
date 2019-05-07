<template>
<v-container pa-0>
  <v-layout>
    <v-flex>
     <h1>{{label}}</h1>
    </v-flex>
   </v-layout>
</v-container>
</template>

<script>
  export default {
    name : "app-headline",
    props :{
      label : {
        type : String,
        default : "Headline"
      }
    },
    data: () => ({
     
    })
  }
</script>

<style>

</style>
