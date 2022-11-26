<!-- eslint-disable max-len -->
<template>
  <div id='us'>
    <div class='container'>
      <p>
        Non so dove vada la mia strada, ma cammino meglio quando la mia mano stringe la tua.
      </p>
      <span>Alfred de Musset</span>
    </div>
    <div class="container">
      <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="@/components/img/image0.jpeg" class="d-block w-100 img-fluid" alt="#">
        </div>
        <div class="carousel-item">
          <img src="@/components/img/image1.jpeg" class="d-block w-100 img-fluid" alt="#">
        </div>
        <div class="carousel-item">
          <img src="@/components/img/image2.jpeg" class="d-block w-100 img-fluid" alt="#">
        </div>
        <div class="carousel-item">
          <img src="@/components/img/image3.jpeg" class="d-block w-100 img-fluid" alt="#">
        </div>
        <div class="carousel-item">
          <img src="@/components/img/image4.jpeg" class="d-block w-100 img-fluid" alt="#">
        </div>
      </div>
      <button class="carousel-control-prev" data-bs-target="#carouselExampleControlsNoTouching"
        data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" data-bs-target="#carouselExampleControlsNoTouching"
        data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    </div>
    <div class="container">
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta at recusandae corrupti earum perferendis assumenda autem aut cumque dignissimos, neque natus quis soluta magnam ipsa illum unde illo pariatur quo?
      Ipsam deserunt vel facere quia necessitatibus corrupti. Atque, eligendi. Fugiat cum, nam voluptatum consequatur laudantium, numquam impedit atque eos labore maiores incidunt facere possimus delectus expedita enim pariatur eaque provident.
      Pariatur veniam eum quam deleniti. Atque numquam, voluptates, corporis est minima impedit aut labore quis amet sunt accusamus quia illum voluptatem ab consequuntur dolorem sit, obcaecati aperiam illo totam ducimus!</p>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang='scss' scoped>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&display=swap');

#us {
  font-family: 'Dancing Script', cursive;
  width: 100%;
  background-color: #5c1923;
}

p {
  color: white;
  font-size: 25px;
}

span{
  color: white;
  margin-left: 50rem;
}

.container {
  text-align: center;
  padding-top: 7rem;
}

img {
  width: 100%;
}

.carousel-item{
  border-radius: 20px;
  overflow: hidden;
  img{
    aspect-ratio: 4 / 3;
    object-fit: cover;
  }
}
</style>
