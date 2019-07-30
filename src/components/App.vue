<template>
  <div>
    <Header></Header>
    {{ message }}
  </div>
</template>


<script>
import Header from './Header';

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
