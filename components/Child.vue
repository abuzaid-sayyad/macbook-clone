<template>
  <div class="flex justify-center">
    <button v-on:click="updateTitle" class="bg-blue-500 rounded-md px-10 py-3 text-base font-medium text-white">Update Title of this!</button>
  </div>
</template>

<script>
export default {
  name: "Child",
  methods:{
    updateTitle(){
      this.$emit('changeTitle', "Props Updated")
    }
  }
}
</script>

<style scoped>

</style>
