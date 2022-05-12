<template>
  <v-container>
    <v-carousel hide-delimiters show-arrows-on-hover cycle>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      ></v-carousel-item>
    </v-carousel>
  <InfoSection/>
  </v-container>
</template>

<script>
  export default {
    head(){
      return{
        title: 'महात्मा गांधी गुरुदत्त स्मारक इंटर कॉलेज, विजयगढ़'
      }
    },
    data () {
      return {
        items: [
          {
            src: 'images/show1.png',
          },
          {
            src: 'images/show2.png',
          },
          {
            src: 'images/show3.png',
          },
          {
            src: 'images/show4.png',
          },
          {
            src: 'images/show5.png',
          },
          {
            src: 'images/show6.png',
          },
        ],
      }
    },
  }
</script>