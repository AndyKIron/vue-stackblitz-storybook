<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <hr />
    <div class="font-chart-1">SharedUI css font-chart-1</div>
    <hr />
    <Typography variant="title">SharedUI Typography title component</Typography>
    <hr />
    <Heading level="3"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit.</Heading
    >
    <hr />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Typography from '@ironsource/shared-ui/typography';
import Heading from '@ironsource/shared-ui/heading';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Heading,
    Typography,
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
