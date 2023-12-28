<template>
  <div>
    <h1
      style="color:#1C1C1F; padding-top: 70px;padding-bottom: 70px; font-style: italic;text-decoration: underline;">
      COMPETENCE</h1>
    <div class="row">
      <div class="col-2"></div>
      <div class="col-8">
        <div class="row">
          <div :class="screenWidth > 1050 ? 'col' : 'col-12'">
            <div class="row mb-1">
              <div class="col-5 t-left">
                JavaScript
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="75"  class="w-75"></b-progress>
              </div>
            </div>
            <div class="row mb-1">
              <div class="col-5 t-left ">
                React js
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="90"  class="w-75" style="color:#b0c0d4;"></b-progress>
              </div>
            </div>
            <div class="row mb-1">
              <div class="col-5 t-left ">

                Vue js


              </div>
              <div class="col-7 pt-1">
                <b-progress :value="75"  class="w-75" style="color:#b0c0d4;"></b-progress>
              </div>

            </div>
            <div class="row mb-1">
              <div class="col-5 t-left">
                Node js
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="90"  class="w-75"></b-progress>
              </div>

            </div>
            <div class="row mb-1">
              <div class="col-5 t-left">
                MongoDB
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="80"  class="w-75"></b-progress>
              </div>

            </div>
          </div>
          <div :class="screenWidth > 1050 ? 'col' : 'col-12'">
            <div class="row mb-1">

              <div class="col-5 t-left ">
                CSS
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="92" class="w-75"></b-progress>
              </div>
            </div>
            <div class="row mb-1">

              <div class="col-5 t-left ">
                HTML
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="95"  class="w-75"></b-progress>
              </div>
            </div>
            <div class="row mb-1">

              <div class="col-5 t-left">
                Bootstrap
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="75"  class="w-75"></b-progress>
              </div>
            </div>
            <div class="row mb-1">

              <div class="col-5 t-left">
                API RESTful
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="87"  class="w-75"></b-progress>
              </div>
            </div>
            <div class="row mb-1">

              <div class="col-5 t-left">
                MYSQL
              </div>
              <div class="col-7 pt-1">
                <b-progress :value="75"  class="w-75"></b-progress>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ComptencePage",
  data() {
    return {
      screenWidth: screen.width,
    }
  },
}
</script>
<style>
.timeline {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
  padding: 40px 20px;
}

.timeline::after {
  content: '';
  position: absolute;
  width: 2px;
  background-color: #000;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -1px;
}

.timeline-item {
  position: relative;
  margin-bottom: 50px;
}

.timeline-item::after {
  content: '';
  position: absolute;
  width: 20px;
  height: 20px;
  background-color: #000;
  border-radius: 50%;
  top: 0;
  left: 50%;
  margin-left: -10px;
}

.timeline-item.left .timeline-content {
  left: 70%;
}

.t-left {
  text-align: left;
  padding-left: 20px;
  padding-right: 20px;
  color: #1C1C1F;
  font-family: Arial, Helvetica, sans-serif;
 
  text-decoration: underline;

}

.timeline-item.right .timeline-content {
  left: 20%;
}
</style>