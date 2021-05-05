<template>
  <section id="EDU">
    <div class="title">
      <h2>Education</h2>

      <div class="wrapper">
        <div class="text-wrapper">
          <p>Where I've been for the past years.</p>
        </div>
      </div>
    </div>
    <div class="section-content">
      <div class="container-fluid">
        <div class="row justify-content-center">
          <div
            class="col-md-7 mr-auto card-mobile"
            style="text-align: left !important;"
          >
            <h4>Bakkeskolen Cosmos</h4>
            <p>From: 2006 - 2016</p>
            <h4>Studie 10</h4>
            <p>From: 2016 - 2017</p>
            <h4>Esbjerg Gymnasium HF</h4>
            <p>From: 2017 - 2019</p>
            <h4>Business Academy SouthWest (EASV) @ MultiMediaDesigner</h4>
            <p>From: 2020 - Current</p>
          </div>
          <div class="col-md-4 card-mobile"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
h4,
p {
  color: white;
   font-weight: 700;
}

img {
  max-width: 100%;
}
.title {
  text-align: center;
  color: black;
  h2 {
     color: white;
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
    border-bottom: 1px solid white;
  }
}
#EDU {
  background-color: #0062cc;
}
@media (min-width: 992px) {
  .section-content {
    width: 80%;
    margin: 0 auto;
  }
}
@media (max-width: 992px) {
  .card-mobile {
    text-align: center !important;
    margin-top: 20px;
  }
}
</style>
