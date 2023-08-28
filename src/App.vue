<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <hr />
    <Typography variant="title">Title</Typography>
    <hr />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Heading from '@ironsource/shared-ui/heading';
import Typography from '~@ironsource/shared-ui/components/v4/Typography.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Typography,
  },
};
</script>

<style>
@import './node_modules/@ironsource/shared-ui/styles/levelplay/fonts.css';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
