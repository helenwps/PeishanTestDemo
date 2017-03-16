<template>
  <div class="login">
    <h1>HELLO MY APP</h1>
    <span>Message is:{{ msg }}</span>
    <input type="text" v-model="msg" placeholder="edit me">
    <router-link to="/register">糟糕！没有账号，赶紧注册一个。</router-link>
  </div>
</template>

<script>
export default {
  name: 'login',
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
