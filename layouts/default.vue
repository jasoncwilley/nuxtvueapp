<template>
  <div>
    <div class="wrapper">
      <app-navigation />
  <app-background />
      <nuxt/>

</div>
    </div>


</template>
<script>
import AppNavigation from './../components/AppNavigation.vue';
import AppBackground from './../components/AppBackground.vue';


export default {
  components: {
    AppNavigation,
    AppBackground,
    }
};
</script>
<style>
body {
  height: 100%;
  margin-left: 25px;
}

.wrapper {

  margin-bottom: -60px;
}
.footer,
.push {
  height: 50px;
  margin-top: 10px;
}
</style>

