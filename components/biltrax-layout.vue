<template>
  <div class="overflow-hidden">
    <biltrax-topbar></biltrax-topbar>
    <div class="w-full max-w-8xl relative mx-auto">
      <div class="lg:flex relatives">
        <biltrax-sidebar></biltrax-sidebar>
        <div class="w-full md:w-5/6 ml-auto overflow-auto bg-gray-100 pt-16">
          <slot></slot>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BiltraxTopbar from "./menus/biltrax-topbar";
import BiltraxSidebar from "./menus/biltrax-sidebar";
export default {
  name: "biltrax-layout",
  components: {BiltraxSidebar, BiltraxTopbar}
}
</script>

<style scoped>

</style>
