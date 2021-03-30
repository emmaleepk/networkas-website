<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <div class="main-card">
      <div class="left-column">
        <div class="info">Info</div>
        <div class="info">Contact</div>
        <div class="info">Mission</div>
      </div>
      <div class="right-column">
        <h2>Info</h2>
        <p>
          Network America Services provides all sorts of useful information.
        </p>
      </div>
    </div>
    <p>
    </p>
  </div>
</template>

<script>
export default {
  name: 'Home',
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
p {
  color: #000000ff;
}
h2 {
  color: #000000ff;
}
.main-card {
  padding: 10px;
  background: #14213dff;
  display: grid;
  grid-gap: 50px 10px;
  grid-template-columns: 33% 66%;
  height: 750px;
}
.left-column {
  background: #9ac6c5ff;
  grid-column-start: 1;
  grid-column-end: 1;
  grid-row-start: 1;
  grid-row-end: 1;
}
.right-column {
  background: #9ac6c5ff;
  grid-column-start: 2;
  grid-column-end: 3;
  grid-row-start: 1;
  grid-row-end: 1;
}
.info {
  padding:20px;
  color: #000000ff;
  cursor: pointer;
}
.info:hover {
  background: #7785acff;
}
</style>
