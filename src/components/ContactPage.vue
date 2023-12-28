<template>
  <div style="background-color:#1c1c1f;height: 60vh;">
    <h1 style="color:#e0e2e8;padding-top: 20px;padding-bottom: 20px;"> CONTACT </h1>
    <div class="contact">
      <div class="icons">

        <i class="bi bi-geo-alt-fill">Siliana Tunisie</i>
        <br>
        <i class="bi bi-telephone">+216 25759338</i>
        <br>
        <i class="bi bi-envelope-open" style="padding-left: 65px;">jamilaguebli02@gmail.com</i>
        <br>
        <br>
        <div class="image1">
          <div class="cart">
            <a href="https://www.linkedin.com/in/guebli-jamila-923ba5251?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
              <i class="bi bi-linkedin" style="color: white;"></i>
              </a>
          </div>
          <div class="cart">

           <a href="https://github.com/jamilaguebli">
              <i class="bi bi-github"  style="color: #e0e2e8;"></i>
            </a>
          </div>
          <div class="cart">
            <a href="https://www.facebook.com/profile.php?id=100071643041119&mibextid=ZbWKwL">
              <i class="bi bi-facebook" style="width: 150px;height: 150px; color: white;"></i></a>
          </div>
        </div>

      </div>
      <div>

        <b-container fluid>
          <b-row>
            <b-col sm="2">
              <label for="textarea-small" style="color:#e0e2e8;font-family: Arial, Helvetica, sans-serif;">name:</label>
            </b-col>
            <b-col sm="10">
              <input id="textarea-small" size="sm" v-model="name">
            </b-col>
          </b-row>

          <b-row class="mt-2">
            <b-col sm="2">
              <label for="textarea-default" style="color: #e0e2e8;font-family: Arial, Helvetica, sans-serif;">Email:</label>
            </b-col>
            <b-col sm="10">
              <input id="textarea-default" v-model="email">
            </b-col>
          </b-row>
         
          <b-row class="mt-2">
            <b-col sm="2">
              <label for="textarea-large" style="color:#e0e2e8;font-family: Arial, Helvetica, sans-serif;">Message: </label>
            </b-col>
            <b-col sm="10">
              <b-form-input id="input-large" size="lg" ></b-form-input>
            </b-col>
          </b-row>

        </b-container>
        <br>
        <b-button variant="outline-secondary">envoyer</b-button>
      </div>
    </div>
  </div>
</template>
<script>

export default {
  name: 'ContactPage',
  

   
}


</script>
<style>
.contact {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;

}

.icons {
  color: #e0e2e8;
  font-family: Arial, Helvetica, sans-serif;
}

.image1 {

  display: flex;
  justify-content: space-around;
  align-items: center;
 
}
#input-large {
    text-align: right;
    color: #333; /* Couleur du texte */
    font-size: 16px; /* Taille de la police */
    /* Marge supérieure */
    padding: 20px; /* Remplissage intérieur */
    /* Ajoutez d'autres styles personnalisés si nécessaire */
}
 
</style>