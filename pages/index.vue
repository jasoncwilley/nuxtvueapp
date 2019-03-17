<template>
<div>

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

<style>
  .grid-container {
    display: grid;
    grid-template-columns: 10px 400px 400px 10px;
    grid-template-rows: 50px 400px 300px 100px;
    grid-template-areas: "side-a navarea navarea side-b" "side-a grid-a grid-b side-b" "side-a grid-a grid-b side-b" "footer footer footer footer";
  }

  .side-a { grid-area: side-a; }

  .side-b { grid-area: side-b; background-color: blue}

  .navarea { grid-area: navarea; }

  .grid-a { grid-area: grid-a; margin-right: 25px}

  .grid-b { grid-area: grid-b; margin-left: 220px; color:black;}

  .footer { grid-area: footer; }

  /* Start http://www.cursors-4u.com */ * {cursor: url(http://cur.cursors-4u.net/mechanics/mec-1/mec77.ani), url(http://cur.cursors-4u.net/mechanics/mec-1/mec77.png), auto !important;} /* End http://www.cursors-4u.com */


body {
  color: white;
}
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 100%;
  margin-right: 25px;
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.card-container {
  padding: 2px 16px;
}
.noresults_card {
  margin-top: 25px;
}
.directions {
  margin-top: 25px;
  font-size: 13px;
}
.search_buttons {
  margin-left: 25px;
}
.button {
  width: 100px;
  margin-right: 35px;
}
.playersearchform {
  margin-top: 120px;
height: 25px;
}
.teamsearchform {
  margin-top: 105px;
height: 25px;
}
</style>

