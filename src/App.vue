<template>
  <div class="container">
    <app-tags v-model="tags" :value="tags" :color="success"/>
  </div>
</template>
<script>
  import Tags from "./components/Tags"
  export default {
    components : {
      appTags : Tags
    },
    data(){
      return{
        tags:"php,laravel,vuejs",
      }
    }
  }
</script>
<style>
  body{
    font-family: sans-serif;
  }
</style>
