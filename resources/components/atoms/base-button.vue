<template>
  <button>
    <nuxt-link
      v-if="to"
      :to="to"
    >
      <slot/>
    </nuxt-link>
    <template v-else>
      <slot/>
    </template>
  </button>
</template>

<script>
export default {

  props: {
    to: {
      type: String,
      default: ''
    }
  },

}
</script>

<style lang="scss">
button {
  display: inline-block;
  border-radius: 4px;
  padding: 10px 30px;
  border: 1px solid #fff;
}
</style>
