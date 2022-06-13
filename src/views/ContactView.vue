<template>
  <div class="contact">
    <h1 class="text-success">This is an contact page</h1>
    <PathFile></PathFile>
  </div>
</template>

<script>
// @ is an alias to /src
import PathFile from '@/components/PathFile.vue'

export default {
  name: 'ContactView',
  components: {
    PathFile
  }
}
</script>
