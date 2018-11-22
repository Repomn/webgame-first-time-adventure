<template>
  <section class="container">
    <div>
      <h1 class="title">
        はじめての冒険
      </h1>
      <h2 class="subtitle">
        My fabulous Nuxt.js project
      </h2>
      <div class="links">
        <base-button
          to="/City">
          AAAAA
        </base-button>
        <base-button>
          BBBBB
        </base-button>
      </div>
    </div>
  </section>
</template>

<script>
import BaseButton from '~/components/atoms/base-button.vue'

export default {
  name: 'AppRoot',

  components: {
    BaseButton
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
