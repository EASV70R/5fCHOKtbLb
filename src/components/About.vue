<template>
  <section id="about">
    <div class="title">
      <h2>About me</h2>
      <div class="photo">
        <a>
          <img src="../assets/img/cj.png" alt="" />
        </a>
      </div>
      <div class="wrapper">
        <div class="text-wrapper">
          <p>
            Hello, my name is Torben. I am currently studying as a
            MultiMedia Designer at Business Academy SouthWest (EASV).
          </p>
          <p>
            My education consist of Web Development/Design and
            Graphic/Photo/Video Design.
          </p>
          <p>In my free time, I usually enjoy toying with video games.</p>
          <a
            href="//"
            class="btn btn-primary btn-x"
            target="_blank"
            >Watch my Video CV!</a
          >
          <h2>&</h2>
          <a href="/cv.pdf" class="btn btn-primary btn-xl"  target="_blank" 
            >Download my CV digitally.</a
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style scoped lang="scss">
.photo {
  a:focus {
    outline: none;
  }
  img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    display: inline-block;
  }
}
img {
  max-width: 100%;
}
.title {
  text-align: center;
  color: black;
  h2 {
    font-size: 4rem !important;
    text-transform: uppercase !important;
  }
}
p {
  color: black !important;
  font-weight: 700 !important;
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
