<template>
  <div id="app">
    <Head/>
    <!--<HelloWorld/>-->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Head from './components/Head.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Head
  }
}
</script>

