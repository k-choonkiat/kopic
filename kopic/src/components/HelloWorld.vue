<template>
  <div>
  <img class=background src= "../assets/tenor.gif">
  <v-container>
  <v-flex xs7 offset-xs5 offset-md5 offset-lg5>
 <v-card
    class="mx-auto"
    max-width="560"
    max-height= "480"
    hover = true  
    raised = 24
  >
    <v-img
      class="white--text align-end justify-center" 
      height="150px"
      width="150px"
      src="../assets/kopi.png">
    </v-img>
    <v-card-text>

      <p class="display-1 text--primary">
        Kopi C
      </p>
      <p>adjective</p>
      <form>
      <label for="email1">Sign up here!</label><br>
      <input type="text" border="solid" placeholder="lim@kopic.com" id="email1"/> <br>
      <button class="button">Subscribe now!</button>
      </form>
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