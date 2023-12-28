<template>
  <div>
    <h1
      style="color:#1c1c1f; padding-top: 70px;padding-bottom: 70px; font-style: italic;text-decoration: underline;">
      Projet
    </h1>
    <div class="card-project">
      <div v-for="(carde, index) in prodCopy " :key="index">
        <b-card  :img-src="carde.imglink" img-alt="Image" img-top tag="article"
          style="max-width: 20rem;" class="mb-2">
          <b-card-text style="color: #1c1c1f;font-family: Arial, Helvetica, sans-serif;">
            {{ carde.description }}
          </b-card-text>
        </b-card>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ProjetPage',
  data() {
    return {
      prodCopy: this.$store.state.cards,
    }
  },

  mounted() {
    // this.prodCopy = this.$store.state.cards;
    // console.log("produit copy");
    // console.log(this.prodCopy);

  },
}
</script>
<style>
.card-project {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
</style>