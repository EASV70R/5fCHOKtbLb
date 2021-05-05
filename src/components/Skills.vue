<template>
  <section id="Skills">
    <div class="title">
      <h2>Skills</h2>

      <div class="wrapper">
        <div class="text-wrapper">
          <p>What I'm good at.</p>
        </div>
      </div>
    </div>
    <div>
      <ul
        style="display: grid;grid-template-columns:repeat(3,1fr); text-align: center !important;"
      >
        <div class="img-container">
          <img src="../assets/img/cplusplus.png" alt="C++" />
        </div>
        <div class="img-container">
          <img src="../assets/img/html.png" alt="HTML" />
        </div>
        <div class="img-container">
          <img src="../assets/img/css.png" alt="CSS" />
        </div>
        <div class="img-container">
          <img src="../assets/img/vuejs.png" alt="VueJS" />
        </div>
        <div class="img-container">
          <img src="../assets/img/ps.png" alt="Adobe Photoshop" />
        </div>
        <div class="img-container">
          <img src="../assets/img/XD.png" alt="Adobe XD" />
        </div>
      </ul>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
p {
  color: black !important;
   font-weight: 700 !important;
}
img {
  width: 50px;
  height: 50px;
  text-align: center;
}
.img-container {
  padding-top: 50px;
  text-align: center;
  display: block;
}
.title {
  text-align: center;
  color: black;
  h2 {
    font-size: 4rem;
    text-transform: uppercase;
  }
}
.text-wrapper {
  &:before {
    content: "";
    width: 150px;
    display: block;
    margin: 20px auto;
    border-bottom: 1px solid black;
  }
}
#Skills {
  background-color: whitesmoke;
}
</style>
