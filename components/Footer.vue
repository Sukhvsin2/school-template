<template>
  <v-footer
    padless
    class="px-0 py-0"
  >
    <v-container fluid class="px-0 py-0">
        <v-card
            flat
            tile
            class="orange lighten-1 white--text text-center"
            >

            <v-row class="my-3">
                <v-col cols="12" lg="4">Tab1</v-col>
                <v-col cols="12" lg="4">Tab2</v-col>
                <v-col cols="12" lg="4">
                    <div class="head">Contact Us</div>
                    <div class="data">
                        <div>Email ID: mggsintercollege@gmail.com</div>
                        <div>Phone Number: +91xxxxxxxxxx
                        </div>
                        <div>Address: MGGS Inter college, Vijaygarh, Aligarh 202170</div>
                    </div>
                </v-col>
            </v-row>

            <v-divider></v-divider>

            <v-card-text class="white--text">
                &copy {{ new Date().getFullYear() }}  Copyright — महात्मा गांधी गुरुदत्त स्मारक इंटर कॉलेज, विजयगढ़
            </v-card-text>
            </v-card>
    </v-container>
  </v-footer>
</template>

<style scoped>
.head{
    font-size: 1.5em;
}

.head .data{
    font-size: 0.8em;
}
</style>