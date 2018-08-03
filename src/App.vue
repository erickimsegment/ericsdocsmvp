// the template tag just contains some simple markdown
<template>
  <router-view id="app"/>
</template>

// this script tag does nothing
<script>
export default { name: 'app' }
</script>

<style lang="scss">
@import './sass/app';
</style>
