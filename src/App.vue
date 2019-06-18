<template>
  <div id="app">
    <transition>
      <keep-alive exclude="Detail">
        <router-view/>
      </keep-alive>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style></style>
