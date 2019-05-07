<template>
  <v-container fluid grid-list-xl>
    <center>
      <v-layout row justify-space-between>
        <v-flex>
          <a @click="$router.push('/')">ลืมรหัสผ่าน</a>
        </v-flex>
        <v-spacer></v-spacer>
        <v-flex>
          <a @click="$router.push('/Register')">สมัครสมาชิก</a>
        </v-flex>
      </v-layout>
    </center>
  </v-container>
</template>
<script>
export default {
  name: "ForgenAndRegis"
};
</script>