<script lang="ts">
import { defineComponent } from "vue";
import Camera from "simple-vue-camera";

export default defineComponent({
    components: {
        Camera,
    },
});



// <script setup>
// import { defineComponent } from 'vue'
// import Camera from 'simple-vue-camera'

// export default defineComponent({
//   components: {
//     Camera
//   }
// })
</script>
<template>
  <h1>cam1↓</h1>
    <camera :resolution="{ width: 375, height: 812 }" autoplay></camera>
</template>