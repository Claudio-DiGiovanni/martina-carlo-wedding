<template>
  <header>
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Noi</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Location</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Informazioni</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Contatti</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container">
      <img class="logo" src="@/components/img/martina & carlo.svg" alt="Martina e Carlo" />
      <img class="date" src="@/components/img/23 . 05 . 2023.png" alt="23-05-2023">
    </div>
  </header>
</template>

<script>
export default {
  name: 'headerPage',
};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css2?family=Nerko+One&display=swap");

header {
  width: 100%;
  height: 50rem;
  background-image: url(@/components/img/background-wine.png);
  background-position: center;
  background-size: cover;
  position: relative;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.logo {
  width: 700px;
}

.date{
  margin-top: -13rem;
}

nav {
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(#5c1923, 80%, transparent);
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 5rem;
  z-index: 100;
}

ul {
  display: flex;
  justify-content: center;
  font-family: "Nerko One", cursive;
}

li {
  margin: 0 2rem;
  cursor: pointer;
}

a {
  text-decoration: none;
  color: white;
  font-size: 20px;
}

.navbar-collapse.show{
  width: 100%;
  height: 100vh;
  background-color: #5c1515;
  position: fixed;
  top: 0;
  left: 0;
  li{
    margin: 4rem;
    a{
      font-size: 50px;
    }
  }
}

#navbarNav {
  display: flex;
  justify-content: center;
}

span{
  filter: invert(100);
}

button{
  z-index: 100;
  :hover{
    border: 1px solid #7c1228;
  }
}
</style>
