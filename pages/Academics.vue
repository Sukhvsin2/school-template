<template>
  <v-container>
        <h2>मान्यता के विषय</h2>

        <v-container>
            <h4 class="my-3">हाईस्कूल स्तर </h4>
            <div>
                <ol>
                    <li>हिन्दी</li>
                    <li>अंग्रेजी</li>
                    <li>गणित</li>
                    <li>विज्ञान</li>
                    <li>सा॰ अध्ययन</li>
                    <li>कारा</li>
                    <li>गृह विज्ञान</li>
                    <li>संस्कृत</li>
                </ol>
            </div>

            <h4 class="my-3">इण्टर स्तर</h4>
            <v-row>
                <v-col>
                    <div class="ml-3">
                        <h5>कला वर्ग</h5>
                        
                        <div>
                            <ol>
                                <li>हिन्दी साहित्यक</li>
                                <li>अंग्रेजी</li>
                                <li>संस्कृत</li>
                                <li>भूगोल</li>
                                <li>अर्थ शास्त्र</li>
                                <li>शिक्षा शास्त्र</li>
                                <li>ना॰ शास्त्र</li>
                            </ol>
                        </div>
                    </div>
                </v-col>
                <v-col>
                    <div class="ml-3">
                    <h5>विज्ञान वर्ग</h5>
                    
                    <div>
                            <ol>
                                <li>हिन्दी सामान्य</li>
                                <li>अंग्रेजी</li>
                                <li>रसायन विज्ञान</li>
                                <li>भूगोल</li>
                                <li>गणित</li>
                            </ol>
                    </div>
                </div>
            </v-col>
            </v-row>
        </v-container>
  </v-container>
</template>

<script>
export default {
    head() {
        return {
            title: "पाठ्यक्रम"
        };
    },
}
</script>

<style>

</style>