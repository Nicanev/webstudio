<template>
<component :is="layout">
<router-view />
</component>
  
</template>

<script>
import MainLayout from "@/layouts/MainLayout";
export default {
  computed: {
    layout() {
      return 'main-layout'
    }
  },
  components: {
    MainLayout
  }

}
</script>
<style lang="scss">
@import 'assets/css/style.min.css';
</style>


