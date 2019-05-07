<template>
  <v-container>
    <v-layout>
      <v-flex>
          <center>
          <v-flex>
            <div style="padding: 20px;">
              <p class="wh body-2">{{item.label}}</p>
            </div>
          </v-flex>
          <v-btn
            @click="$router.push('/queue')"
            style="width: 300px;"
            :body-style="{ padding: 0 }"
          >
            
              <v-img style="width: 100%" rounded="circle" :src="item.image_url"></v-img>
            
          </v-btn>
        </center>
      </v-flex>
    </v-layout>
  </v-container>
</template>
<script>
export default {
  props: {
    item: {
      type: Object,
      default: function() {
        return {
          label: "คุณสมบัติ",
          image_url:
            "https://cdn.vox-cdn.com/thumbor/_73Mw9kZ1ZdH1M7IUusMGQNf4TA=/0x0:960x768/1200x800/filters:focal(424x378:576x530)/cdn.vox-cdn.com/uploads/chorus_image/image/56732615/ubereatsFB.0.jpg"
        };
      }
    }
  }
};
</script>