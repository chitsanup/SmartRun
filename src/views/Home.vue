<template>
<v-container pa-0>
  <v-layout column="hidden-sm-and-up">
    <v-flex mb-2>
      <AppCover/>
    </v-flex>
  </v-layout>
  <v-layout>
    <v-flex>
      
    </v-flex>
  </v-layout>
  <v-layout>
    <v-flex>
      <ModeZone2/>
    </v-flex>
  </v-layout>
  <v-layout>
    <v-flex>
      <ModeZone3/>
    </v-flex>
  </v-layout>
</v-container>
  
</template>

<script>
  import AppCover from '../components/AppCover'
  import ModeZone2 from '../components/ModeZone2'
  import ModeZone3 from '../components/ModeZone3'
  export default {
    components: {
      AppCover,
      ModeZone2,
      ModeZone3,
    }
  }
</script>
