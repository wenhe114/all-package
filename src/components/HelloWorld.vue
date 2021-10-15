<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ace></ace>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import ace from "@pack/vue3-ace/src/vue3-ace.vue"
export default defineComponent({
  name: "HelloWorld",
  components:{
    ace
  },
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
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
