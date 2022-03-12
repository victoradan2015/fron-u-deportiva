<template>
  <div class="hello">
    <nav class="toggleable=md navbar navbar-light bg-primary justify-content-between">
      <a class="navbar-brand text-light" href="#">
        <img src="/docs/4.0/assets/brand/bootstrap-solid.svg" width="30" height="30" class="d-inline-block align-top" alt="">
        Ricardo Farías
      </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          
        </button>

        <form class="form-inline my-2 my-lg-0">
          <button class="btn btn-outline-success bg-success text-light my-2 my-sm-0" type="submit">Search</button>
        </form>
    </nav>
  </div>
</template>

<script>

export default {
  components: { },
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>