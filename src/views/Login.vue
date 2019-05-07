<template>
<v-container pa-0>
  <v-layout column="hidden-sm-and-up">
    <v-flex>
      <Logo/>
    </v-flex>
    <v-flex>
      <FormLogin/>
    </v-flex>
    <v-flex>
      <ForgetAndRegis/>
    </v-flex>
  </v-layout>
</v-container>
  
</template>

<script>
  import FormLogin from '../components/Form/FormLogin'
  import ForgetAndRegis from '../components/ForgetAndRegis'
  import Logo from '../components/Image/Logo'
  export default {
    components: {
      FormLogin,
      ForgetAndRegis,
      Logo
    }
  }
</script>
