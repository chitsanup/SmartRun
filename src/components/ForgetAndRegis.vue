<template>
  <v-container fluid grid-list-xl>
    <v-layout row justify-space-between>
      <v-flex xs6>
        <a @click="$router.push('/')">ลืมรหัสผ่าน</a>
      </v-flex>
      <v-flex xs4>
        <a @click="$router.push('/Register')">สมัครสมาชิก</a>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  name: "ForgenAndRegis"
};
</script>