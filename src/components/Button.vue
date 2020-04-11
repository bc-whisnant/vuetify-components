<template>
  <v-container>
    <v-row>
      <v-btn @click=consoleIt>Click Me</v-btn>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    methods: {
      consoleIt() {
        console.log('Just a test')
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>
