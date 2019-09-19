<template>
  <div class="home">
    <dropzone></dropzone>
  </div>
</template>

<script>
// @ is an alias to /src
import Dropzone from '@/components/Dropzone.vue'

export default {
  name: 'home',
  components: {
    Dropzone
  }
}
</script>
