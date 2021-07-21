<template>
  <div>
    <nav class="navbar mx-4" role="navigation" aria-label="main navigation">
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
        <div class="navbar-end mr-6">
          <nuxt-link to="/" class="navbar-item has-text-primary has-text-weight-bold is-size-6"> Home </nuxt-link>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable has-text-weight-bold is-size-6">
            <a class="navbar-link has-text-primary">
              About us
            </a>

            <div class="navbar-dropdown is-right">
              <a class="navbar-item">
                Our Work
              </a>
              <a class="navbar-item">
                Our Services
              </a>
              <a class="navbar-item">
                About Homelessness
              </a>
              <a class="navbar-item">
                Job Vacancies
              </a>
            </div>
          </div>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable has-text-weight-bold is-size-6">
            <a class="navbar-link has-text-primary">
              Residents
            </a>

            <div class="navbar-dropdown is-right">
              <a class="navbar-item">
                Report a Repair
              </a>
              <a class="navbar-item">
                Paying Rent
              </a>
              <a class="navbar-item">
                Anti-social Behaviour
              </a>
              <a class="navbar-item">
                Useful Information
              </a>
              <a class="navbar-item">
                Case Studies
              </a>
              <a class="navbar-item">
                Downloads
              </a>
            </div>
          </div>
          
          <nuxt-link to="/" class="navbar-item has-text-primary has-text-weight-bold is-size-6"> Referrals </nuxt-link>

          <div class="navbar-item has-dropdown has-text-primary is-hoverable has-text-weight-bold is-size-6">
            <a class="navbar-link has-text-primary">
              Partners
            </a>

            <div class="navbar-dropdown is-right">
              <a class="navbar-item">
                Property Owners
              </a>
              <a class="navbar-item">
                Housing Associations
              </a>
              <a class="navbar-item">
                About Homelessness
              </a>
              <a class="navbar-item">
                Job Vacancies
              </a>
            </div>
          </div>

          <nuxt-link to="/" class="navbar-item has-text-primary has-text-weight-bold is-size-6"> Contact </nuxt-link>

          <nuxt-link to="/" class="navbar-item has-text-white has-text-weight-bold is-size-6 has-background-primary"> Get Involved </nuxt-link>
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
    background-color: #ffffff0d;
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
</style>