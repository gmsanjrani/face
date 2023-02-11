<template>
  <div>
    <h1>Face Detection</h1>
    <video ref="video" autoplay style="display: none"></video>
    <canvas ref="canvas" width="600px" height="400px"></canvas>
  </div>
</template>

<script>
import setup from "./script"
export default {
data() {
    return {

    }
},
methods: {

},
  mounted() {
    setup(this.$refs.video, this.$refs.canvas)
  }
}
</script>

<style lang="scss" scoped></style>
