<template>
<v-container pa-0>
  <v-layout column="hidden-sm-and-up">
    <v-flex>
      <Logo/>
      <Login/>
      <ForgetAndRegis/>
    </v-flex>
  </v-layout>
  <v-layout>
    <v-flex>
      
    </v-flex>
  </v-layout>
</v-container>
  
</template>

<script>
  import Login from '../components/Login'
  import ForgetAndRegis from '../components/ForgetAndRegis'
  import Logo from '../components/Logo'
  export default {
    components: {
      Login,
      ForgetAndRegis,
      Logo
    }
  }
</script>
