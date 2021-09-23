<template>
  <v-container class="my-15">
    <v-row justify="center">
      <v-col lg="12" class="text-center">
        <v-subheader class="text-h4 justify-center">Contact</v-subheader>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam,
          commodi?
        </p>
      </v-col>
      <v-col lg="6">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d420063.508052096!2d135.13910908847538!3d34.66111312108016!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6000e86b2acc70d7%3A0xa399ff48811f596d!2z5aSn6Ziq5bqc!5e0!3m2!1sja!2sjp!4v1632317560552!5m2!1sja!2sjp"
          width="100%"
          height="100%"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
        ></iframe>
      </v-col>
      <v-col lg="6">
        <v-form ref="form" >
          <v-text-field
            v-model="contactInfo.name"
            :counter="10"
            label="Name"
            required
          ></v-text-field>

          <v-text-field
            v-model="contactInfo.email"
            label="E-mail"
            required
          ></v-text-field>
            <v-textarea label="Message" v-model="contactInfo.message"></v-textarea>

          <v-btn color="success" class="mr-4"> Send </v-btn>
        </v-form>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: "Contactus",
    data(){
        return{
            contactInfo:{}
        }
    }
};
</script>

<style>
</style>