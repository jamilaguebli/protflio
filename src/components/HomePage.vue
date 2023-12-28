<template>
    <div>
        <div  class="home">
    <div class="image">
    <img :src=" imageSrc" alt="jamila">
     </div>  
     <h1 style="color: #1C1C1F;">Jamila Guebli</h1>
     <h5 style="color: #1C1C1F;">Développeur Full Stack</h5>
     <br>

     <div style="background-color:white; width:100%; padding-left: 15%; padding-right: 15%; height: 350px; font-size: 25px;" class="center-text">
     
      <div style="color:#394054;text-align: center; font-family: Arial, Helvetica, sans-serif;font-size: 23px;">
        Enthousiaste développeur web débutant avec une passion pour la création d'expériences 
        utilisateur dynamiques et performantes. Maîtrise des technologies modernes telles que
         React.js, Vue.js et Node.js pour concevoir et implémenter des applications web
          interactives. Fortes compétences en résolution de problèmes,
           collaboration d'équipe et engagement envers la qualité du code.
            Prêt à relever de nouveaux défis et à continuer d'apprendre pour évoluer dans le
             domaine du développement web.
        
    </div>
    </div>

     </div>
     </div>
     
    


    

</template>
<script>
export default {
  name: 'HomePage',
  data() {
    return {
      imageSrc:require("../assets/jamila.jpg") ,
    };
  },
}
</script>
<style>
.image img{
    width:200px ;
    border-radius: 50%;
}
.home{
  
    height:95vh;
    padding-top: 70px;
   
}



 div h1{
    color: white;

}
div h5{
    color: white;
}



</style>