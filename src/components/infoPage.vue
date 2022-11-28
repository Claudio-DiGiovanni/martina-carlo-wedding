<!-- eslint-disable max-len -->
<template>
<div id="info">
  <div class="container">
    <div class="text-center my-5">
      <h3>La nostra favola inizia qui! Grazie a tutti voi perchè contribuendo ci aiutate a realizzarla nel modo migliore</h3>
      <span class="d-block my-4">IBAN: IT30U0760117300001004180418</span>
      <span class="d-block my-4">Intestato a Carlo Spina</span>
    </div>
  </div>
  <video autoplay muted loop id="myVideo">
    <source src="@/components/img/pexels-roman-odintsov-5657050.mp4" type="video/mp4">
  </video>
</div>
</template>

<script>
export default {

};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Merienda:wght@300;400;500;600;700;800;900&display=swap');

#info{
    background-color: #5c1923;
    color: white;
    font-family: 'Merienda', cursive;
    text-align: center;
    margin-top: -5px;
  }

  h3{
    font-size:40px;
    margin-bottom: 2rem;
  }

  video{
    width: 100%;
    padding: 5rem 0;
  }

  span{
    font-size: 20px;
  }
</style>
