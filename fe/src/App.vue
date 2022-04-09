<template>
  <v-app>
    <v-main>
      <SignUp />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SignUp from './components/SignUp.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
    SignUp
  },

  data: () => ({
    //
  }),
}
</script>
