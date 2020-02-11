<template>
  <div>
  <img class=background src= "../assets/tenor.gif">
  <v-container>
  <v-flex xs7 offset-xs5 offset-md5 offset-lg5>
  <v-row align="center" justify="center">
 <v-card
    class="mx-auto"
    min-width="300"
    min-height= "300"
    elevation = 24
    hover = true  
    raised = 24
  >
    <v-img
      class="white--text align-end justify-center" 
      height="250px"
      width="300px"
      background-position = "right"
      src="../assets/kopi.png">
    </v-img>
    <v-card-text>

      <v-card-title class="headline">
        Kopi C
      </v-card-title>
      <v-card-subtitle>Subscribe here!</v-card-subtitle>
        <v-form
    ref="form"
    v-model="valid"
    lazy-validation
  >


    <v-text-field
      v-model="email"
      :rules="emailRules"
      label="E-mail"
      required
    ></v-text-field>


    <v-btn
      :disabled="!valid"
      color="success"
      class="mr-4"
      @click="validate"
    >
      Submit
    </v-btn>


  </v-form>
    </v-card-text>
    <v-card-actions>
      <v-btn
        text
        color="deep-purple accent-4"
      >
        Learn More
      </v-btn>
    </v-card-actions>
  </v-card>
  </v-row>
  </v-flex>
  </v-container>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({
   
  })
};
</script>
<style>
.background {
  /* Set rules to fill background */
  min-height: 100%;
  min-width: 1024px;
	
  /* Set up proportionate scaling */
  width: 100%;
  height: auto;
	
  /* Set up positioning */
  position: fixed;
  top: 0;
  left: 0;
}

.position{
  margin-left: 15%;
  height: 200px;
}

</style>