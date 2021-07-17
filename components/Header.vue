<template>
  <div>
    <b-navbar class="navbar p-2">
      <template #brand>
        <b-navbar-item tag="router-link" :to="{ path: '/' }" class="brand-text has-text-weight-bold">
          REST SERVICES
        </b-navbar-item>
      </template>

      <template #end>
        <b-navbar-item href="#" class="nav-item has-text-white has-text-weight-bold is-size-4 mx-1 mt-4"> About </b-navbar-item>
        <b-navbar-item href="#" class="nav-item has-text-white has-text-weight-bold is-size-4 mx-1 mt-4"> Contact </b-navbar-item>
        <b-navbar-item href="#" class="mr-6 nav-item has-text-white has-text-weight-bold is-size-4 mx-1 mt-4"> Services </b-navbar-item>
        <b-navbar-item tag="div">
          <div class="buttons">
            <a class="button is-primary is-rounded new-button has-background-white button-white">
              <strong>Book Appointment</strong>
            </a>
          </div>
        </b-navbar-item>
      </template>
    </b-navbar>
  </div>
</template>

<script>

export default {
  name: 'Header',
}
</script>

<style scoped>
  .navbar {
    background-color: #ffffff0d;
    position: fixed;
    top: 0;
    width: -webkit-fill-available;
  }

  .brand-text {
    -webkit-text-fill-color: transparent;
    -webkit-text-stroke: 0.5px white;
  }

  .button-white {
    color: #056c5f;
  }

  .button-white:hover {
    border-color: white !important;
    background-color: transparent !important;
  }

  .nav-item {
    height: fit-content;
  }

  .nav-item:hover {
    background-color: #ffffff29;
    -webkit-text-fill-color: transparent;
    -webkit-text-stroke: 0.03px white;
    border: 1px solid white;
    border-radius: 10px;
  }
</style>