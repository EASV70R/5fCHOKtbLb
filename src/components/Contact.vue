<template>
  <section id="contact">
    <div class="title">
      <h2>Contact Info</h2>
      <div class="wrapper">
        <div class="text-wrapper"></div>
      </div>
    </div>

    <div class="section-content">
      <div class="container-fluid">
        <div class="row justify-content-center">
          <ul
            style="display: grid;grid-template-columns:repeat(3,1fr); text-align: center !important;"
          >
            <li>
              <a
                href="mailto:torb1843@easv365.dk"
                class="btn btn-default btn-lg"
                ><i class="fa fa-mail fa-fw"></i>
                <span class="network-name">Email</span></a
              >
            </li>
            <li>
              <a
                href="https://github.com/easvt0r"
                class="btn btn-default btn-lg"
                ><i class="fa fa-github fa-fw"></i>
                <span class="network-name">Github</span></a
              >
            </li>
            <li>
              <a
                href="https://www.linkedin.com/in/ahahahahahaha/"
                class="btn btn-default btn-lg"
                ><i class="fa fa-link fa-fw"></i>
                <span class="network-name">LinkedIn</span></a
              >
            </li>
          </ul>
        </div>
        <hr />
        <h4>Address: Spangsbjerg Kirkevej 103, 6700 Esbjerg</h4>
        <h4>Email: torb1843@easv365.dk</h4>
        <h4>Tlf: +45 00000000</h4>
        <div class="row justify-content-center">
          <div
            class="col-md-7 mr-auto card-mobile"
            style="text-align: center !important;"
          ></div>
          <div class="col-md-4 card-mobile"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
span {
  color: black;
  font-weight: 700;
}
h4 {
  font-size: 18px;
  color: black;
  font-weight: 700;
}
.row {
  padding-top: 20px;
  text-align: left;
}
hr {
  max-width: 50px;
  margin-left: auto;
  margin-right: auto;
  border-color: #0062cc;
  border-width: 3px;
}
p {
  color: black;
  font-weight: 700;
}
hr.light {
  border-color: #fff;
}
img {
  max-width: 100%;
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
#about {
  background-color: whitesmoke;
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
