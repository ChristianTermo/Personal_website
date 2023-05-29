<template>
  <div>
    <div class="background">
      <img src="../assets/vue.png" alt="" class="vue" />
      <img src="../assets/laravel.png" alt="" class="laravel" />
      <img src="../assets/spring.png" alt="" class="spring" />
      <img src="../assets/javascript.png" alt="" class="javascript" />
      <img src="../assets/bootstrap.png" alt="" class="bootstrap" />
      <img src="../assets/mysql.png" alt="" class="mysql" />
      <img src="../assets/git.png" alt="" class="git" />
        <div class="arrow">
        <span></span>
        <span></span>
        <span></span>
    </div>
    </div>

    <!--<div class="icondivbutton">
      <img
        src="../assets/icon.png"
        alt=""
        srcset=""
        class="iconbutton"
        ref="hamburger"
        @click="openMenu"
      />
    </div>
    <div class="background"></div>
    <div class="sidebar" ref="sidebar" v-bind:style="{ width: computedWidth }">
      <div style="padding-top: 11px">
        <h3>Dashboard</h3>
      </div>
      <hr />
      <div class="container">
        <div>
          <img src="../assets/icons-user.png" alt="" class="iconitemelement" />
        </div>
        <div>
          <a href="#aboutme" class="sidebar-item"><div>About me</div></a>
        </div>
      </div>
      <hr />
      <div class="container">
        <div>
          <img
            src="../assets/icons-technologies.png"
            alt=""
            srcset=""
            class="iconitemelement"
          />
        </div>
        <div>
          <a href="#tecnologie" class="sidebar-item"><div>Tecnologie</div></a>
        </div>
      </div>
      <hr />
      <div class="container">
        <div>
          <img
            src="../assets/icons-contact.png"
            alt=""
            class="iconitemelement"
          />
        </div>
        <div>
          <a href="#contatti" class="sidebar-item"><div>Contatti</div></a>
        </div>
      </div>
      <hr />
      <div class="container">
        <div>
          <img
            src="../assets/icons-github.png"
            alt=""
            class="iconitemelement"
          />
        </div>
        <div>
          <a href="https://github.com/ChristianTermo" class="sidebar-item"><div>Github</div></a>
        </div>
      </div>
      <hr />
      <div class="container">
        <div>
          <img src="../assets/icons-lang.png" alt="" class="iconitemelement" />
        </div>

        <div class="btn-group dropend">
          <button
            type="button"
            class="btn btn-secondary dropdown-toggle"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
            Lingua
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">IT</a></li>
            <li><a class="dropdown-item" href="#">EN</a></li>
          </ul>
        </div>
      </div>
      <div class="closebutton">
        <br />
        <button type="submit" class="btn btn-light" @click="closeMenu">
          Chiudi
        </button>
      </div>
      
    </div>-->
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false,
      width: "0px",
      display: "none",
    };
  },

  computed: {
    computedWidth: function () {
      return this.width;
    },

    computedDisplay: function () {
      return this.display;
    },
  },

  methods: {
    openMenu: function () {
      this.menuOpen = true;
      this.display = "block";
      this.width = "350px";
    },

    closeMenu: function () {
      this.menuOpen = false;
      this.display = "none";
      this.width = "0px";
    },
  },
};
</script>

<style>
@import "../css/background.css";
</style>