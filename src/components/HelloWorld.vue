<template>
  <div class="hello">

    <div class="topnav">
      <div>
        <h2 style="color:#E0E2E8; font-weight: 800;">JAMILA</h2>
      </div>
      <div>
        <ul>
          <li style="color: #E0E2E8;"><a href="#HomePage" >Home</a></li>
          <li style="color: #E0E2E8;"><a href="#FormationPage" >Formation</a></li>
          <li><a href="#ExperiencePage" >Expérience</a></li>
          <li><a href="#ComptencePage" >Compétence</a></li>
          <li><a href="#ProjetPage" >Projet</a></li>
          <li><a href="#ContactPage" >Contact</a></li>
        </ul>
      </div>
    </div>

    <div>
      <div>
        <section id="HomePage" style="overflow-y: auto; overflow-x: hidden;">

          <home-page />
        </section>
      </div>
      <div>
        <section id="FormationPage" style="overflow-y: auto; overflow-x: hidden;">
          <formation-page />
        </section>
        <br>
      </div>
      <div>
        <section id="ExperiencePage" style="overflow-y: auto; overflow-x: hidden;">
          <experience-page />
        </section>
      </div>
      
      <div>
        <section id="ComptencePage" style="overflow-y: auto; overflow-x: hidden;">
          <comptence-page />
        </section>
      </div>
      <div>
        <section id="ProjetPage" style="overflow-y: auto; overflow-x: hidden;">
          <projet-page />
        </section>
      </div>
      <br>
      <br>
      <div>
        <section id="ContactPage" style="overflow-y: auto; overflow-x: hidden;">
          <contact-page />
        </section>
      </div>
    </div>



  </div>
</template>

<script>

import HomePage from '../components/HomePage.vue'
import FormationPage from '../components/FormationPage.vue'
import ExperiencePage from '../components/ExperiencePage.vue'
import ComptencePage from '../components/ComptencePage.vue'
import ContactPage from '../components/ContactPage.vue'
import ProjetPage from '../components/ProjetPage.vue'
export default {
  name: 'HelloWorld',
  components: {
    HomePage,
    FormationPage,
    ExperiencePage,
    ComptencePage,
    ContactPage,
    ProjetPage
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
  color: rgb(113, 112, 112);

}

li {
  display: inline-block;
  margin: 0 10px;
  color: rgb(123, 118, 118);




}

img {
  width: 100px;
  height: 50px;
}

a {
  color: #e5eeee;

}

.topnav li:hover {
  background-color: #5DA5B3;

}

.topnav a {


  text-decoration: none;
  font-size: 15px;


}

.topnav {
  background-color:#1C1C1F;
  position:fixed;
  width: 100%;
  height: 50px;
  display: flex;
  justify-content: space-between;
}
 li a{
  color: E8EDDF;
}
</style>
