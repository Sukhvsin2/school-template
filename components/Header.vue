<template>
<div>
    <v-app-bar
      color="amber accent-4"
      flat
      dark
    >

      <v-toolbar-title>
        <n-link to="/" text>
          महात्मा गांधी गुरुदत्त स्मारक इंटर कॉलेज, विजयगढ़
        </n-link>
      </v-toolbar-title>

      <v-spacer></v-spacer>

       <v-btn x-large to="/message" text>
        <div>संदेश</div>
      </v-btn>
      
      <v-btn x-large to="/sports" text>
        <div>तस्वीरें</div>
      </v-btn>

      <v-btn x-large to="/academics" text>
        <div>पाठ्यक्रम</div>
      </v-btn>
      <v-btn x-large to="/contacts" text>
        <div>संपर्क करें</div>
      </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        
      }
    },
  }
</script>
<style>

</style>