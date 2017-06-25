<template>
  <div class="intro">
    <h1>FUTURE DEVS CLUB</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'intro',
  data () {
    return {
      msg: 'A place for 👩🏻‍💻future devs👨🏾‍💻 to get fun resources and start coding projects🤙!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 0;
}
</style>
