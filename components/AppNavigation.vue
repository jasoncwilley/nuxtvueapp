<template>
  <div>
    <div class="navarea">
        <link href="https://fonts.googleapis.com/css?family=Fugaz+One" rel="stylesheet">
          <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">
          <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous">

       <nav class="navbar navbar-expand-md fixed-top">
          <a class="navbar-brand" href="#"><img src="http://oi66.tinypic.com/15frdpc.jpg" height="55px" width="55px"> </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
          </button>


              <ul class="navbar-nav mr-auto">
                  <nuxt-link to="/"><button class="btn">Home</button></nuxt-link>
                   <nuxt-link to="/playersearch"><button class="btn">Player Search</button></nuxt-link>
                    <nuxt-link to="/teamsearch"><button class="btn">Team Search</button></nuxt-link>
                    <nuxt-link to="/arrestdetails"><button class="btn">Arrest Details</button></nuxt-link>
              </ul>


    </nav>
    </div>

  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
.navarea {
max-width: 800px;
text-align: center;
  height: 70px;
  background-color: white;
  margin-left: 25px;
  margin-bottom: 25px;
  }

ul {
  padding-top: 20px;
  display: flex;
  list-style-type: none;
  justify-content: center;
  align-items: center;
  }

button {
  padding: 0 10px;
  font-family: 'Fugaz One', cursive;
  font-size: 20px;
  color:rgb(212, 11, 27);
  position: relative;
  display: inline;
  border-width: 3px;
  border-color: blue;
  margin-bottom: 20px;
  margin-right: 20px;

}
</style>
