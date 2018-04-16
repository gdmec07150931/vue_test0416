<template>

  <div id="myheader">
    <div class="">
      <img src="../assets/images/logo.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyHeader',
  data () {
    return {
      text: 1,
      status: true
    }
  },
  methods: {
    add () {
      console.log('methods----abc')
      this.text = this.text + 1
      this.status = !this.status
    },
    minus () {
      console.log('methods---minus')
      this.text = this.text - 1
    }
  }

}
</script>

<style>

</style>
