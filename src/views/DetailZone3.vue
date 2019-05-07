<template>
  <v-container pa-0>
    <v-layout mb-2>
      <v-flex>
        <v-img
          aspect-ratio="2.8"
          style
          src="https://blog.wiggle.co.uk/sites/default/files/styles/770x480crop/public/hero/comp_2.jpg?itok=RP6Sw84X"
          fab
          large
          dark
        >
          <center>
            <v-layout pa-2 column>
              <v-spacer></v-spacer>
              <v-flex>
                <h1>Zone3</h1>
              </v-flex>
            </v-layout>
          </center>
        </v-img>
      </v-flex>
    </v-layout>
    <v-layout ml-2 row justify-space-between>
      <v-flex>
        <p>เหมาะสำหรับ</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <p>-ผู้ที่ออกกำลังกายเป็นประจำ</p>
        <p>-ต้องการควบคุมน้ำหนักหรือลดลงเล็กน้อย</p>
        <p>-เพื่อเพิ่มความฟิต ลดไขมัน ลดน้ำตาลในเลือด</p>
        <p>-มีเวลาออกกำลังกายต่อเนื่อง (10-30 นาที)</p>
      </v-flex>
    </v-layout>
    <hr>
    <v-layout ml-2 mt-2 row justify-space-between>
      <v-flex>
        <p>อัตราการเต้นของหัวใจ</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <p>70% - 80% ของอัตราการเต้นของหัวใจสูงสุด</p>
      </v-flex>
    </v-layout>
    <hr>
    <v-layout ml-2 mt-2 row justify-space-between>
      <v-flex>
        <p>ลักษณะการวิ่ง</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <img src="../assets/Zone3.png">
      </v-flex>
    </v-layout>
    <hr>
    <v-layout>
    <v-flex>
      <v-flex>
        <v-btn @click="$router.push('/Home')" block color="error" dark>ตกลง</v-btn>
      </v-flex>
    </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  components: {}
};
</script>