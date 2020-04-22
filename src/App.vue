<template>
  <div id="page-container">
    <app-header></app-header>
    <router-view id="content-wrap" />
    <footer id="footer">
      <app-footer></app-footer>
    </footer>
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader";
import AppFooter from "@/components/AppFooter";

export default {
  name: "app",
  components: {
    AppHeader,
    AppFooter
  }
};
</script>

<style>
#page-container {
  position: relative;
  min-height: 100vh;
  padding-bottom: 6rem;
}
#footer {
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
