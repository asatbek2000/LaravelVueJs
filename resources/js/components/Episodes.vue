<template>
  <div>
      <a :href="video.url" v-for="(video,index) in videos" class="text-decoration-none" style="color:black">

          <b-card
      no-body
      class="overflow-hidden"
      style="width: 100%; margin-top: 2rem"
    >
      <b-row no-gutters>
        <b-col md="3">
          <b-button>{{video.episode_number}}</b-button>
        </b-col>
        <b-col md="9">
          <b-card-body :title="video.title">
            <b-card-text>
              {{video.description.substring(0,200) + ' ...'}}
            </b-card-text>
          </b-card-body>
        </b-col>
      </b-row>
    </b-card>

      </a>

  </div>
</template>

<script>
export default {
  props: ["videos"],
  mounted() {
    console.log("Component mounted.");
  },
};
</script>
