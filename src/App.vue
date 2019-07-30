<template>
  <div>
    <Header></Header>
    {{ message }}
  </div>
</template>


<script>
import Header from './components/Header';

export default {
  name: 'App',
  components: { Header },
  data() {
    return {
      message: 'Hello Vue!'
    }
  }
}
</script>

<style lang="scss">
    @import "./scss/common.scss"
</style>
