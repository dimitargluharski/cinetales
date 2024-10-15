<script setup>
import { BNavbar, BNavbarBrand } from 'bootstrap-vue-3'
</script>

<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="m-auto">
          <b-nav-form>
            <b-form-input class="w-96" placeholder="Search"></b-form-input>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
