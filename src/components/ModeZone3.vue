<template>
  <v-container pa-0>
    <v-layout>
      <v-flex>
        <center>
          <v-flex style="padding: 20px;">
            <h1 class="wh body-2">สำหรับกระชับกล้ามเนื้อ</h1>
            <button
              @click="$router.push('/DetailZone3')"
              style="width: 100%;"
              :body-style="{ padding: 0 }"
            >
              <v-img
                aspect-ratio="2"
                src="https://blog.wiggle.co.uk/sites/default/files/styles/770x480crop/public/hero/comp_2.jpg?itok=RP6Sw84X"
              >
                <center><v-layout pa-2 column fill-height>
                  <v-spacer></v-spacer>
                  <v-flex shrink>
                    <h1>Zone3</h1>
                  </v-flex>
                </v-layout>
                </center>
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