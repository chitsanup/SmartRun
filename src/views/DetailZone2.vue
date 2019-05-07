<template>
  <v-container pa-0>
    <v-layout mb-2>
      <v-flex>
        <v-img
          aspect-ratio="2.8"
          style
          src="https://img3.thelist.com/img/gallery/signs-youre-jogging-incorrectly/youre-not-exactly-a-yogi.jpg"
          fab
          large
          dark
        >
          <center>
            <v-layout pa-2 column>
              <v-spacer></v-spacer>
              <v-flex>
                <h1>Zone2</h1>
              </v-flex>
            </v-layout>
          </center>
        </v-img>
      </v-flex>
    </v-layout>
    <v-layout ml-2>
      <v-flex>
        <p>เหมาะสำหรับ</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <p>-ผู้ที่มีน้ำหนักตัวมาก ยังไม่สามารถออกกำลังกายหนักๆได้นานๆ</p>
        <p>-ต้องการลดน้ำหนักมากๆ</p>
        <p>-มีเวลาออกกำลังกายนานๆ (40-80 นาที)</p>
      </v-flex>
    </v-layout>
    <hr>
    <v-layout ml-2 mt-2>
      <v-flex>
        <p>อัตราการเต้นของหัวใจ</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <p>60% - 70% ของอัตราการเต้นของหัวใจสูงสุด</p>
      </v-flex>
    </v-layout>
    <hr>
    <v-layout ml-2 mt-2>
      <v-flex>
        <p>ลักษณะการวิ่ง</p>
      </v-flex>
      <v-flex>
        <p>:</p>
      </v-flex>
      <v-flex xs8>
        <img src="../assets/Zone2.png">
      </v-flex>
    </v-layout>
    <hr>
    <v-flex>
      <v-flex>
        <v-btn @click="$router.push('/Home')" block color="error" dark>ตกลง</v-btn>
      </v-flex>
    </v-flex>
  </v-container>
</template>
<script>
export default {
  components: {}
};
</script>