<template>
  <div id="app">
    <div id="avatar_container"> 
      <Avatar/>
    </div>
  </div>
</template>

<script>
import Avatar from './components/Avatar.vue'

export default {
  name: 'app',
  components: {
    Avatar
  }
}
</script>

<style>
#app {

}
#avatar_container {
  width: 400px;
  height: 400px;
}
</style>
