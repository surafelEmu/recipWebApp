<template>
  <v-app>
    <v-main>
      <Popup />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Recipe from './components/Recipe.vue'
import PopUp from './components/popUp.vue'
import Popup from './components/popup.vue'
export default {
  name: 'App',

  components: {
    HelloWorld,
    Recipe ,
    PopUp , 
    Popup
  },

  data: () => ({
    
  }),
}
</script>
