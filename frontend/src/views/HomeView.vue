<script>
export default {
  data() {
    return {
      msg: 'Hello World!'
    }
  }
}
</script>

<template>
  <main>
    <h1>{{ msg }}</h1>
  <input v-model="msg">
  </main>
</template>
