<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  height: 100%;
  margin: 0;
  padding: 0;
}
.home,
.agent,
.call {
  margin: 10px 40px;
}
table,
th,
td {
  border: 1px solid black;
}
table {
  table-layout: fixed;
  width: 100%;
  border-collapse: collapse;
}
th,
tr {
  width: 30%;
}
</style>
