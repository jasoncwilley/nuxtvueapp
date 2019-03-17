<template>
<div>
<app-navigation />
<app-background />
</div>
</template>

<script>
import AppLogo from './../components/AppLogo.vue';
import AppNavigation from './../components/AppNavigation.vue';
import AppBackground from './../components/AppBackground.vue';
export default {
  components: {
    AppLogo,
    AppNavigation,
    AppBackground
}
}
</script>
