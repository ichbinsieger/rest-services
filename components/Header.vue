<template>
  <div>
    <nav class="navbar padded-nav" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <nuxt-link class="navbar-item" to="/">
          <div class="brand-text has-text-weight-bold">
            REST SERVICES
          </div>
        </nuxt-link>

        <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link to="/" class="navbar-item has-text-primary has-text-weight-semibold is-size-6"> Home </nuxt-link>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable is-size-6">
            <nuxt-link to="/about" class="navbar-link has-text-primary has-text-weight-semibold">
              About us
            </nuxt-link>

            <div class="navbar-dropdown is-right has-background-primary has-text-white">
              <nuxt-link to="/about#wehelp" class="navbar-item has-text-white  dropdown-item">
                Our Work
              </nuxt-link>
              <nuxt-link to="/services" class="navbar-item has-text-white  dropdown-item">
                Our Services
              </nuxt-link>
              <nuxt-link to="/about#homelessness" class="navbar-item has-text-white  dropdown-item">
                About Homelessness
              </nuxt-link>
              <a class="navbar-item has-text-white  dropdown-item">
                Job Vacancies
              </a>
            </div>
          </div>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable is-size-6">
            <nuxt-link to="/residents" class="navbar-link has-text-primary has-text-weight-semibold">
              Residents
            </nuxt-link>

            <div class="navbar-dropdown is-right has-background-primary has-text-white">
              <nuxt-link to="/residents" class="navbar-item has-text-white  dropdown-item">
                Report a Repair
              </nuxt-link>
              <nuxt-link to="/residents" class="navbar-item has-text-white  dropdown-item">
                Paying Rent
              </nuxt-link>
              <nuxt-link to="/residents" class="navbar-item has-text-white  dropdown-item">
                Anti-social Behaviour
              </nuxt-link>
              <nuxt-link to="/residents#useful-information" class="navbar-item has-text-white  dropdown-item">
                Useful Information
              </nuxt-link>
              <a class="navbar-item has-text-white  dropdown-item">
                Case Studies
              </a>
              <nuxt-link to="/residents#downloads" class="navbar-item has-text-white  dropdown-item">
                Downloads
              </nuxt-link>
            </div>
          </div>
          
          <nuxt-link to="/referral" class="navbar-item has-text-primary has-text-weight-semibold is-size-6"> Referrals </nuxt-link>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable is-size-6">
            <nuxt-link to="/partners" class="navbar-link has-text-primary has-text-weight-semibold">
              Partners
            </nuxt-link>

            <div class="navbar-dropdown is-right has-background-primary has-text-white">
              <nuxt-link to="/partners" class="navbar-item has-text-white  dropdown-item">
                Property Owners
              </nuxt-link>
              <nuxt-link to="/partners#associations" class="navbar-item has-text-white  dropdown-item">
                Housing Associations
              </nuxt-link>
              
            </div>
          </div>

          <nuxt-link to="/contact" class="navbar-item has-text-primary has-text-weight-semibold is-size-6"> Contact </nuxt-link>

          <nuxt-link to="/get-involved" class="navbar-item has-text-white has-text-weight-semibold is-size-6 has-background-primary"> Get Involved </nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>

export default {
  name: 'Header',
}
</script>

<style scoped>
  .navbar {
    background-color: #ffffff;
    box-shadow: 0 0 9px #000 !important;
    position: fixed;
    top: 0;
    width: -webkit-fill-available;
  }

  .brand-text {
    -webkit-text-fill-color: transparent;
    -webkit-text-stroke: 0.5px #003B56;
  }

  .button-white {
    color: #056c5f;
  }

  .button-white:hover {
    border-color: white !important;
    background-color: transparent !important;
  }

  .nav-item {
    color: #003B56 !important;
  }

  .nav-item:hover {
    /*background-color: #ffffff29;
    -webkit-text-fill-color: transparent;
    -webkit-text-stroke: 0.03px white;
    border: 1px solid white;
    border-radius: 10px;*/
  }

  .navbar-link:not(.is-arrowless)::after {
    border-color: #003B56 !important;
  }

  .navbar-end {
    border-bottom: 3px solid #003B56;
  }

  .dropdown-item:hover {
    background-color: #ffffff21 !important;
  }

  .padded-nav {
    padding-left: 104px !important;
    padding-right: 104px !important;
  }
</style>