<!-- eslint-disable max-len -->
<template>
  <div id="contacts">
    <div class="container">
      <div class="row g-5">
        <div class="col-12 col-md-7">
          <p>Siete pregati di confermare la Vostra presenza entro il 23.04.2023 ai nostri contatti e di specificare eventuali intolleranze alimentari o problemi specifici</p>
        </div>
        <div class="col-12 col-md-5 contatti">
          <h4 class="my-3">Numeri di telefono</h4>
          <span>Martina +393475090218</span>
          <span>Carlo +393454624342</span>
          <h4 class="my-3">Email</h4>
          <span>martina.almasio@virgilio.it</span>
          <span>spinacarlo.sc@virgilio.it</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  #contacts {
  background-color: #5c1923;
  padding: 3rem 0;
  color: white;
  font-family: 'Merienda', cursive;
  }

  .contatti{
    display: flex;
    flex-direction: column;
  }
</style>
