<template>
  <h1> {{ message }}</h1>
  <HelloWorld/>
</template>

<script>
  import HelloWorld from '~/components/Helloworld'

  export default {
    components : {
      HelloWorld
    },
    data() {
      return {
        message: '뭐야 어려워!'
      }
    }
  }
</script>