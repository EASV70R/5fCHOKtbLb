<template>
  <header class="header bgimg">
    <div class="name">
      <div class="wrapper-name">
        <h1>Torben</h1>

        <hr />

        <p>Hello there!</p>
        <a href="#about" class="btn btn-primary btn-xl"
          >Get to know me!</a
        >
      </div>
    </div>
  </header>
</template>

<script></script>

<style scoped lang="scss">
.header {
  padding: 20px;
  background-color: black;
}
.bgimg {
  background-image: url("../assets/img/bg.jpeg");
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100%;
}
.name {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  margin: 0 auto;
  z-index: 400;
  .wrapper-name {
    width: 250px;
  }
  h1 {
    font-size: 2.3rem;
    padding: 2px 10px;
    text-align: center;
    text-transform: uppercase;
    color: white;
  }
  p {
    font-size: 1.5rem;
    text-align: center;
    margin: 5px auto;
    color: white;
  }
  hr {
    max-width: 50%;
    margin-left: auto;
    margin-right: auto;
    border: 1px solid #0062cc;
  }
}
.btn-default {
  border-color: #fff;
  color: #222;
  background-color: #fff;
  -webkit-transition: all 0.35s;
  -moz-transition: all 0.35s;
  transition: all 0.35s;
}

.btn-default:hover,
.btn-default:focus,
.btn-default.focus,
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  border-color: #ededed;
  color: #222;
  background-color: #f2f2f2;
}

.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}

.btn-default.disabled,
.btn-default[disabled],
fieldset[disabled] .btn-default,
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus,
.btn-default.disabled:active,
.btn-default[disabled]:active,
fieldset[disabled] .btn-default:active,
.btn-default.disabled.active,
.btn-default[disabled].active,
fieldset[disabled] .btn-default.active {
  border-color: #fff;
  background-color: #fff;
}

.btn-default .badge {
  color: #fff;
  background-color: #222;
}

.btn-primary {
  border-color: Color(172, 172, 172);
  color: #fff;
  background-color: Color(172, 172, 172);
  -webkit-transition: all 0.35s;
  -moz-transition: all 0.35s;
  transition: all 0.35s;
}

.btn-primary:hover,
.btn-primary:focus,
.btn-primary.focus,
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  border-color: Color(172, 172, 172);
  color: #fff;
  background-color: Color(172, 172, 172);
}

.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}

.btn-primary.disabled,
.btn-primary[disabled],
fieldset[disabled] .btn-primary,
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus,
.btn-primary.disabled:active,
.btn-primary[disabled]:active,
fieldset[disabled] .btn-primary:active,
.btn-primary.disabled.active,
.btn-primary[disabled].active,
fieldset[disabled] .btn-primary.active {
  border-color: #f05f40;
  background-color: #f05f40;
}

.btn-primary .badge {
  color: #f05f40;
  background-color: #fff;
}

.btn {
  border: 0;
  border-radius: 300px;
  text-transform: uppercase;
  font-family: "Open Sans", "Helvetica Neue", Arial, sans-serif;
  font-weight: 700;
}

.btn-xl {
  padding: 15px 30px;
}
@media (min-width: 768px) {
  .name {
    .wrapper-name {
      width: 55%;
    }
    h1 {
      font-size: 2.8rem;
      padding: 4% 8%;
    }
    p {
      font-size: 2rem;
    }
  }
}
@media (min-width: 992px) {
  .name {
    .wrapper-name {
      width: 450px;
    }
    h1 {
      font-size: 4rem;
      padding: 4% 10%;
    }
    p {
      font-size: 2.5rem;
    }
  }
}
@media only screen and (max-device-width: 1024px) {
  .bgimg {
    background-attachment: scroll;
  }
}
</style>
