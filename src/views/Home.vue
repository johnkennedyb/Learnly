<template  style="background-color: #367EC6">
  <v-app  style="background-color: #367EC6" >
    <NavBar  style="background-color: #000000" />
    <v-main  style="background-color: #367EC6">
<v-container>
        <v-row>
         
          <v-toolbar color="transparent">

           
          </v-toolbar>
          <v-col cols="12" sm="12" class="mt-n10">
            <Popular />
          </v-col>
          <v-toolbar color="transparent" class="mt-n10">
           
          </v-toolbar>
          <v-col cols="12" sm="12" class="mt-n10">
            <Featured />
          </v-col>
         

         
        </v-row>
      </v-container>
      <Footer style="background-color: #000000" />
    </v-main>
  </v-app>
</template>

<script setup>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";
import Popular from "@/components/Popular.vue";
import Featured from "@/components/Featured.vue";
</script>
<script>
export default {
  data() {
    return {
      items: [
        {
          src: "7.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
        {
          src: "1.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
        {
          src: "2.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
        {
          src: "3.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
        {
          src: "4.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
        {
          src: "5.jpg",
          title: "Surface Studio",
          text: "Le lorem ipsum est, en imprimerie, une suite de mots sans signification utilisée à titre provisoire pour calibrer une mise en page, le texte définitif venant remplacer le faux-texte dès ",
        },
      ],
    };
  },
};
</script>
<style scoped>
.top {
  margin-top: 100px;
}
.text {
  margin-top: -40px;
  margin-left: 80px;
}
.top-day {
  margin-top: 120px;
}
</style>
