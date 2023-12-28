<template>
    <div>
        <h1
            style="color: #1c1c1f; padding-top: 70px;padding-bottom: 70px; font-style: italic;text-decoration: underline;">
            FORMATION</h1>
        <br />
        <br />
        <div class="formation">
            <div class="row w-75">
                <div :class="screenWidth > 1050 ? 'col-5' : 'col-12'">
                    <div class="timeline-content " >
                        <div class="timeline-date" style="color:#394054;">2017-2018</div>
                        <b class="bi bi-backpack-fill" style="color:#1c1c1f;font-family: Arial, Helvetica, sans-serif;">Baccalauréat Informatique</b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">Lycée Kesra Siliana-Tunisie</div>
                    </div>
                    <div class="timeline-content">
                        <div class="timeline-date" style="color:#394054;">2021-2022</div>
                        <b class="bi bi-backpack-fill" style="color:#1c1c1f; font-family: Arial, Helvetica, sans-serif;">Licence Appliqué en Technologie des Réseaux
                        </b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">Institut Supérieur de Mathématiques Appliquées <br>et
                            d'informatique
                            de Kairouan-Tunisie</div>
                    </div>
                    <div class="timeline-content">
                        <div class="timeline-date" style="color:#394054;">2021-2022</div>
                        <b class="bi bi-backpack-fill" style="color: #1c1c1f;font-family: Arial, Helvetica, sans-serif; ">1 ère Mastère Professionnel en
                            Administration<br>
                            et Sécurité des Systèmes et Réseaux </b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">Institut Supérieur de Mathématiques Appliquées <br>et
                            d'informatique
                            de Kairouan-Tunisie</div>
                    </div>
                </div>
                <div class="col-2"></div>
                <div :class="screenWidth > 1050 ? 'col-5' : 'col-12'">
                    <div class="timeline-content ">
                        <div class="timeline-date" style="color:#394054;">Nov 2022-Jan 2023</div>
                        <b class="bi bi-backpack-fill" style="color: #1c1c1f;font-family: Arial, Helvetica, sans-serif;">Formation Introduction To Web
                            Developement </b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">GOMYCODE-Sousse-Tunisie</div>
                    </div>
                    <div class="timeline-content ">
                        <div class="timeline-date" style="color:#394054;">Jan 2022-Avr 2023</div>
                        <b class="bi bi-backpack-fill" style="color: #1c1c1f;font-family: Arial, Helvetica, sans-serif; ">Formation Front-End
                            with React js</b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">GOMYCODE-Sousse-Tunisie</div>
                    </div>
                    <div class="timeline-content " :style="screenWidth > 1050 ? 'text-align: left;height: 150px;':  'text-align: left;height: 200px;'">
                        <div class="timeline-date" style="color:#394054;">Mai 2022-Juin 2023</div>
                        <b class="bi bi-backpack-fill" style="color: #1c1c1f;font-family: Arial, Helvetica, sans-serif; ">Formation Back-End
                            widh Node js </b>
                        <div class="timeline-description" style="color:#394054;font-family: Arial, Helvetica, sans-serif;">GOMYCODE-Sousse-Tunisie</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>


export default {
    name: "FormationPage",
    data() {
        return {
            screenWidth: screen.width,
        }
    },
    components: {

    }
}
</script>
<style>


.timeline-content {
    text-align: left;
    position: relative;
    left: 10px;
}


.timeline-date {
    font-weight: bold;
    margin-bottom: 10px;
}

.timeline-description {
    margin-bottom: 10px;
}

.formation {
    display: flex;
    margin-left: 20px;
    align-items: center;
    margin-right: 20px;
    flex-wrap: wrap;
    justify-content: space-around;


}</style>