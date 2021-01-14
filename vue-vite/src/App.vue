<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
    <NewCOmponent />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NewCOmponent from './components/NewCOmponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NewCOmponent
  }
}
</script>
