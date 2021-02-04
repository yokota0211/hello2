<template>
  <div class="container">
    <p>{{ message }}</p>
    <router-link to="/price">Price Page test</router-link>
  </div>
</template>

<script>
export default {
  data: function(){
    return{
      message: 'Hello!'
    }
  }
}
</script>

<style>

</style>
