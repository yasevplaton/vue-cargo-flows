<template lang="pug">
  input(
    :type="type"
    :class="classArray"
    :name="name"
    :id="inputId"
  )        
</template>

<script>
export default {
  props: {
    type: String,
    classArray: String,
    inputId: String,
    name: {
      type: String,
      default: ""
    }
  }
};
</script>

<style lang="scss">

</style>
