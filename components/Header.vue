<template>
  <CBox>
    <b-navbar>
      <template #brand>
        <b-navbar-item tag="router-link" :to="{ path: '/' }">
          REST SERVICES
        </b-navbar-item>
      </template>

      <template #end>
        <b-navbar-item href="#"> About </b-navbar-item>
        <b-navbar-item href="#"> Contact </b-navbar-item>
        <b-navbar-item href="#"> Services </b-navbar-item>
        <b-navbar-item tag="div">
          <div class="buttons">
            <a class="button is-primary is-rounded">
              <strong>Book Appointment</strong>
            </a>
          </div>
        </b-navbar-item>
      </template>
    </b-navbar>
  </CBox>
</template>

<script>

export default {
  name: 'Header',
}
</script>
