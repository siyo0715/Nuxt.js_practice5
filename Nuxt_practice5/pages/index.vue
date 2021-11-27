<template>
  <section class="container">
    <div class="header">
      <h1>{{ message }}</h1>
    </div>
    <hr>
  </section>
</template>
 
  
<script>
export default {
  data: function(){
    return {
      message: 'Topページです'
    }
  }
}
</script>
<style>
  h1 {
    color: red;
  }
</style>