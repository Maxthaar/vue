<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
      <p>Hello World!</p>
      <CustomerList />
  </div>
</template>

<script>
import CustomerList from "./CustomerList";

export default {
  name: 'HelloWorld',
  components: {CustomerList},
  props: {
    msg: String
  }
}
</script>
<style>
body{
  background: rgba(71,94,108,1);
}
h1{
  color: rgba(1,170,162,1);
}
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
