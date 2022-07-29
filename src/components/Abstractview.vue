<template>
  <div id="hello">
      <h2>{{ msg }} </h2> 
      <p> {{txt}} </p>
  </div>
</template>
<script>
export default {
  name: "Abstractview",
  props: {
    msg: String,
    txt: String
  }
};
</script>
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
#hello{
  background-color: #FFF;
  padding: 20px;
  border: 2px solid black;
  margin-top: 20px;
  margin-left: 400px;
  margin-right: 400px;
}

container h2 {
  padding: 0;
  margin: 0;
}

</style>
