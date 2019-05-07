<template>
<v-container pa-0>
  <v-layout column="hidden-sm-and-up">
    <v-flex>
      <Logo/>
    </v-flex>
    <v-flex>
      <FormRegister/>
    </v-flex>
  </v-layout>
</v-container>
  
</template>

<script>
  import FormRegister from '../components/Form/FormRegister'
  import Logo from '../components/Image/Logo'
  export default {
    components: {
      FormRegister,
      Logo
    }
  }
</script>
