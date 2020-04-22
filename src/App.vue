<template>
<div>
  <app-header>
    </app-header>
<div>
  <router-view/>
  </div>
 <footer class="fluid-container">
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
    AppFooter,
    
  }
};
</script>

<style lang="scss">

</style>
