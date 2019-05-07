<template>
<!-- -->
  <v-container pa-0 grid-list-md>
          <v-layout column>
            <v-flex xs6 v-for="i in mode" v-bind:key="i.id">
              <food-recommend :item="i"/>
              </v-flex>
            </v-layout>
  </v-container>
</template>

<script>
import Mode from "@/components/Mode"
import axios from 'axios';

import {sync,call} from 'vuex-pathify';

  export default {
    name : "list-mode",
    components:{
      Mode,
    },
    data: () => ({
      
    })

  }
</script>

<style>
 
</style>
