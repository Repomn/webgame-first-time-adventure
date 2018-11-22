<template>
  <div>
    <nuxt/>
  </div>
</template>

<style lang="scss">
@import "~assets/scss/reset.scss";

@font-face {
  src: url("~assets/PixelMplus12-Regular.ttf");
  font-family: "PixelMplus12"
}

html {
  font-family: 'PixelMplus12', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #000;
  color: #fff;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
  color: inherit;
}

a {
  text-decoration: none;
}
</style>
