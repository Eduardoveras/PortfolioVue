<template>
<div>
    <md-toolbar class="title-bar md-transparent" md-elevation="0">
      <h3 class="md-display-1" style="flex: 1">Eduardo Veras</h3>
      <md-button>About</md-button>
      <md-button>Portfolio</md-button>
      <md-button>Contact</md-button>
    </md-toolbar>

  <div class="side-icons inline">
    <md-icon class="md-size-1x">opacity</md-icon>
    <br/>
    <md-icon  class="md-size-1x">menu</md-icon>
    <br/>
    <md-icon class="md-size-1x">toll</md-icon>
    <br/>
    <md-icon class="md-size-1x">loyalty</md-icon>
    <br/>
    </div>
    <div class="inline">
      <p class="md-display-4">Creative <br/>Developer </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Head',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.side-icons{
  padding: 25vh 2.5rem;
  width: 30%
}

.side-icons > *{
  padding: 30px;
}

.title-bar{
  padding:2rem;
}
.title-bar *:not(:first-child) {
    padding-right: 100px;
}

div.inline { float:left; }

</style>
