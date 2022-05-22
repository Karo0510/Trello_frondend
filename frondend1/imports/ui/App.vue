<template>
  <v-app>
   <h1>adam</h1>
      <header>
        <router-link to="/login">
          Login
        </router-link>
        <router-link to="/register">
          Register
        </router-link>
        <router-view></router-view>
      </header>

  </v-app>
</template>



<script>
import { Meteor } from 'meteor/meteor';
import { Tracker } from 'meteor/tracker';

export default {
};
</script>


<style scoped>

</style>