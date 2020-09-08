<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template slot-scope="{ toggle, isToggled }">
      <router-link v-popover:popover1 class="navbar-brand" to="/">
        Jules Spender
      </router-link>
      <el-popover
        ref="popover1"
        popper-class="popover"
        placement="bottom"
        width="200"
        trigger="hover"
      >
        <div class="popover-body">
          Jules Spender.
          <br>
          Data Scientist Developer
        </div>
      </el-popover>
    </template>
    <template slot="navbar-menu">
      <drop-down
              tag="li"
              title="    Pages"
              icon="now-ui-icons design_image"
              class="nav-item"
      >
        <nav-link to="/profile">
          <i class="now-ui-icons education_paper"></i> About Me
        </nav-link>
        <nav-link to="/landing">
          <i class="now-ui-icons users_circle-08"></i> Interest
        </nav-link>
        <nav-link to="/">
          <i class="now-ui-icons users_single-02"></i> Home
        </nav-link>
      </drop-down>
      <li class="nav-item">
        <a
                class="nav-link"
                rel="tooltip"
                title="Follow me on Github"
                data-placement="bottom"
                href="https://github.com/SpenderJ"
                target="_blank"
        >
          <i class="fab fa-github"></i>
          <p class="d-lg-none d-xl-none">Github</p>
        </a>
      </li>
      <li class="nav-item">
        <a
                class="nav-link"
                rel="tooltip"
                title="Follow me on Linkedin"
                data-placement="bottom"
                href="https://www.linkedin.com/in/jules-spender-927a69135/"
                target="_blank"
        >
          <i class="fab fa-linkedin"></i>
          <p class="d-lg-none d-xl-none">Linkedin</p>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script>
import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    DropDown,
    Navbar,
    NavbarToggleButton,
    NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>
