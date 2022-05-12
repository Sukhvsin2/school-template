<template>
    <v-container>
        <v-row></v-row>
          <v-row>
            <v-col
            v-for="n in 8"
            :key="n"
            class="d-flex child-flex"
            cols="12"
            lg="4"
            sm="6"
            >
            <v-img
                :src="`images/img${n}.jpg`"
                cover
                :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
                aspect-ratio="1"
                class="grey lighten-2"
            >
                <template v-slot:placeholder>
                <v-row
                    class="fill-height ma-0"
                    align="center"
                    justify="center"
                >
                    <v-progress-circular
                    indeterminate
                    color="grey lighten-5"
                    ></v-progress-circular>
                </v-row>
                </template>
            </v-img>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    head() {
        return {
            title: "तस्वीरें"
        };
    },
    data(){
        return{
            data: [
                
            ]
        }
    }
}
</script>

<style scoped>

</style>