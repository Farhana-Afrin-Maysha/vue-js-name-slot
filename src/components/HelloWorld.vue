<template>
  <div>
    <LoginLayout>
      <template v-slot:title>This is a Title from  helloworld.vue component</template>
      <template v-slot:text>This is also a text from helloworld.vue component</template>
    </LoginLayout>
  </div>
</template>

<script>
import LoginLayout from "./layouts/LoginLayout";
export default {
  name: "HelloWorld",
  data() {
    return {};
  },
  components: {
    LoginLayout
  }
};
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