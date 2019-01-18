<template>
  <div>
    <b-navbar toggleable type="light" variant="light">
      <b-navbar-toggle target="nav_text_colapse"></b-navbar-toggle>
      <b-navbar-brand>myapp</b-navbar-brand>
      <b-collapse is-nav id="nav_text_collapse">
        <b-navbar-nav>
          <b-nav-text>Home</b-nav-text>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Willkommen im Lappenexpress'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
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