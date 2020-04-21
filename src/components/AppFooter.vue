<template>
<footer class="fluid-container">
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">Adoptme.Org</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item v-bind:to="{name: 'Purpose'}">WHAT we do</b-nav-item>
        <b-nav-item  v-bind:to="{name: 'About'}">WHO we are</b-nav-item >
        <b-nav-item  v-bind:to="{name: 'Events'}">ADOPTION events</b-nav-item >
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</footer>
</template>

<script>
export default {
    name: 'app-footer'
}
</script>

<style scoped>
fluid-container {
    margin-bottom: 0px
}
</style>