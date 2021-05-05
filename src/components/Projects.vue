<template>
  <section id="Project">
    <div class="title">
      <h2>Projects</h2>

      <div class="wrapper">
        <div class="text-wrapper">
          <p>Projects that I have created.</p>
        </div>
      </div>
    </div>

    <div class="container-fluid">
      <div class="row no-gutter">
       
        <div class="col-lg-4 col-sm-6">
          <a class="portfolio-box">
            <img
              src="../assets/img/screen_106.png"
              class="img-responsive"
              alt=""
              style="width: 605px; height: 378px;"
            />
            <div class="portfolio-box-caption">
              <div class="portfolio-box-caption-content">
                <div class="project-category text-faded">
                  OceanCare
                </div>
                <div class="project-name">
                  OceanCare is a project that was created to show people how
                  much garbage is thrown into the ocean.
                </div>
              </div>
            </div>
          </a>
        </div>
        <div class="col-lg-4 col-sm-6">
          <a class="portfolio-box">
            <img
              src="../assets/img/screen.png"
              class="img-responsive"
              alt=""
              style="width: 605px; height: 378px;"
            />
            <div class="portfolio-box-caption">
              <div class="portfolio-box-caption-content">
                <div class="project-category text-faded">
                  Short Movie
                </div>
                <div class="project-name">
                  A School project.
                </div>
              </div>
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">

p {
   color: white;
   font-weight: 700 !important;
}

.portfolio-box {
  display: block;
  position: relative;
  margin: 0 auto;
  max-width: 650px;
}

.portfolio-box .portfolio-box-caption {
  display: block;
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 100%;
  text-align: center !important;
  color: #fff;
  opacity: 0;
  background: #0879f141;
  -webkit-transition: all 0.35s;
  -moz-transition: all 0.35s;
  transition: all 0.35s;
}

.portfolio-box .portfolio-box-caption .portfolio-box-caption-content {
  position: absolute;
  top: 50%;
  width: 100%;
  text-align: center;
  transform: translateY(-50%);
}

.portfolio-box
  .portfolio-box-caption
  .portfolio-box-caption-content
  .project-category,
.portfolio-box
  .portfolio-box-caption
  .portfolio-box-caption-content
  .project-name {
  padding: 0 15px;
  font-family: "Open Sans", "Helvetica Neue", Arial, sans-serif;
}

.portfolio-box
  .portfolio-box-caption
  .portfolio-box-caption-content
  .project-category {
  text-transform: uppercase;
  font-size: 14px;
  font-weight: 600;
}

.portfolio-box
  .portfolio-box-caption
  .portfolio-box-caption-content
  .project-name {
  font-size: 18px;
}

.portfolio-box:hover .portfolio-box-caption {
  opacity: 1;
}

@media (min-width: 768px) {
  .portfolio-box
    .portfolio-box-caption
    .portfolio-box-caption-content
    .project-category {
    font-size: 16px;
  }

  .portfolio-box
    .portfolio-box-caption
    .portfolio-box-caption-content
    .project-name {
    font-size: 22px;
  }
}

img {
  max-width: 100%;
}
.title {
  text-align: center;
  color: white;
  h2 {
    font-size: 4rem !important;
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
#Project {
  background-color: #0062cc;
}
</style>
