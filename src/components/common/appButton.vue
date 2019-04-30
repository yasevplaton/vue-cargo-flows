<template lang="pug">
  button(
    :type="type"
    :class="classArray"
    :id="btnId"
  ) {{text}}        
</template>

<script>
export default {
  props: {
    type: String,
    classArray: String,
    btnId: String,
    text: String
  }
};
</script>

<style lang="scss">

</style>
