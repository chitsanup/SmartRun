<template>
  <v-container pa-0>
    <v-layout>
      <v-flex>
        <center>
          <v-flex style="padding: 20px;">
            <h1 class="wh body-2">สำหรับลดไขมัน</h1>
            <button
              @click="$router.push('/DetailZone2')"
              style="width: 100%;"
              :body-style="{ padding: 0 }"
            >
              <v-img
                aspect-ratio="2"
                
                src="https://img3.thelist.com/img/gallery/signs-youre-jogging-incorrectly/youre-not-exactly-a-yogi.jpg"
              >
                <v-layout pa-2 column fill-height>
                  <v-spacer></v-spacer>
                  <v-flex shrink>
                  <h1>Zone2</h1>
                  </v-flex>
                </v-layout>
              </v-img>
            </button>
          </v-flex>
        </center>
        <hr>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  props: {
    item: {
      type: Object
    }
  }
};
</script>