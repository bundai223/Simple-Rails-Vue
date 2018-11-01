<template>
  <div id="app">
    <p>{{ message }}</p>
    <input v-model='message'>
    <table border="1">
      <tr>
        <th>param</th>
        <th>value</th>
      </tr>
      <tr>
        <td>message</td>
        <td>{{message}}</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      message: "Hello Vue!"
    }
  }
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
}
</style>
