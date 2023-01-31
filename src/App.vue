<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
@font-face {
  font-family: "Monaco";
  src: url("./fonts/monaco-webfont.woff");
}

#app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 101.5%;
  padding: 2px;
}

* {
  font-family: "Monaco", Consolas, Lucida Console, monospace;
  margin: 0;
  padding: 0;
  border: 0;
}

html,
body {
  height: 99%;
  width: 99%;
}
</style>
