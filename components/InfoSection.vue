<script setup>

</script>

<template>
    <v-container>
        <v-row>
            <v-col lg="9" sm="12">
                <v-card
                    class="mx-auto"
                >
                    <v-card-text>
                    <p class="text-h4 text--primary">
                        संस्थापक
                    </p>
                    <p>Message</p>
                    <div class="text--primary">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                         tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, 
                         quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                         Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu 
                         fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in 
                         culpa qui officia deserunt mollit anim id est laborum.
                    </div>
                    </v-card-text>
                    <v-card-actions>
                    <v-btn
                        text
                        color="teal accent-4"
                        to="/home"
                    >
                        Learn More
                    </v-btn>
                    </v-card-actions>
                </v-card>
            </v-col>
            <v-col lg="3" sm="12">
                <!-- <v-card
                    class="mx-auto"
                    color="#26c6da"
                    dark
                    max-width="400"
                >
                    <v-card-title>
                    <v-icon
                        large
                        left
                    >
                        mdi-twitter
                    </v-icon>
                    <span class="text-h6 font-weight-light">Twitter</span>
                    </v-card-title>

                    <v-card-text class="text-h5 font-weight-bold">
                    "Turns out semicolon-less style is easier and safer in TS because most gotcha edge cases are type invalid as well."
                    </v-card-text>

                    <v-card-actions>
                    <v-list-item class="grow">
                        <v-list-item-avatar color="grey darken-3">
                        <v-img
                            class="elevation-6"
                            alt=""
                            src="https://avataaars.io/?avatarStyle=Transparent&topType=ShortHairShortCurly&accessoriesType=Prescription02&hairColor=Black&facialHairType=Blank&clotheType=Hoodie&clotheColor=White&eyeType=Default&eyebrowType=DefaultNatural&mouthType=Default&skinColor=Light"
                        ></v-img>
                        </v-list-item-avatar>

                        <v-list-item-content>
                        <v-list-item-title>Principal</v-list-item-title>
                        </v-list-item-content>
                    </v-list-item>
                    </v-card-actions>
                </v-card> -->
                <v-card>
                    <img
                        height="250px"
                        width ="250px"
                        
                        src="~/assets/sideShow.jpg"
                        />
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<style>

</style>