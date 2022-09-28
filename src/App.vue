<template>
  <div id="app">
    <hello
      >Slot called
      <template v-slot:myslot>named slot</template>
    </hello>
  </div>
</template>

<script>
import hello from './components/HelloWorld.vue';
export default {
  name: 'App',
  components: {
    hello,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
