<template>
  <div>
    <h1>Startseite</h1>
    <p>Dies ist die Startseite.</p>
    <NuxtLink to="/about">Über mich</NuxtLink>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  transition: 'index'
}
</script>

<style>
  .index-enter-active, .index-leave-active { transition: all .5s; }
  .index-enter, .index-leave-active { opacity: 0; transform: translateY(20px) }
</style>
