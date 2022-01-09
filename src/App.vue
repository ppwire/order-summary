<template>
  <router-view class="flex justify-center"></router-view>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Varela+Round&display=swap");
#app {
  font-family: "Varela Round", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 40px;
}

body {
  background-image: url("./assets/pattern-background-desktop.svg");
  background-size: contain;
  background-repeat: no-repeat;
  background-color: #e0e8ff;
  justify-content: center;
}

@media screen and (max-width: 640px) {
  body {
    background-image: url("./assets/pattern-background-mobile.svg");
    background-size: contain;
    background-repeat: no-repeat;
    background-color: #e0e8ff;
    justify-content: center;
  }
}
</style>
