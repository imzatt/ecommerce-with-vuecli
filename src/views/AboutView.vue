<template>
  <div class="about">
    <h1 class="text-danger">This is an about page</h1>
    <PathFile parent="About page"></PathFile>
  </div>
</template>

<script>
// @ is an alias to /src
import PathFile from '@/components/PathFile.vue'

export default {
  name: 'AboutView',
  components: {
    PathFile
  }
}
</script>
