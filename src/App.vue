<template>
<v-app>
  <div id="app">
    <login></login>
    </div>
    </v-app>
</template>

<script>
import login from './components/login';
// import register from './components/registration';
export default {
  name: 'App',

  components: {
    login,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* background-color: green; */
  /* margin-top: 10px;  */
}

</style>

