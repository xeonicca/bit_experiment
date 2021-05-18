<template>
  <button class="button">{{ buttonText }}</button>
</template>

<script>
export default {
  props: {
    buttonText: {
      type: String,
      default: ''
    }
  }
}
</script>

<style lang="less" src="./style.less"></style>