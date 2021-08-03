<template>
  <div class="kids-future">
    <Nav />
    <div class="container-fluid">
      <div class="row">
        <div class="col-12 col-lg-3 offset-lg-2">
          <Hero />
        </div>
        <div class="col-12 col-lg-6">
          <RightSide />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped>
  .kids-future {
    background: black no-repeat center center fixed;
    background-size: cover;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
  }
</style>