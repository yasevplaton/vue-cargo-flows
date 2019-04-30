<template lang="pug">
  #main-interface-wrapper.main-interface-wrapper.main-interface-wrapper--dark
    .container
      .row.greeting-row
        .col-lg-12
          h5.title.title__main Hello! Welcome to the master of building cargo flow maps!
</template>

<script>
export default {
  
};
</script>

<style lang="scss">
.main-interface-wrapper {
  z-index: 1;
  position: absolute;
  background: rgba(255, 255, 255, 0.95);
  border-radius: 5px;
  top: 5px;
  left: 5px;
  padding-top: 10px;
  padding-bottom: 10px;
  max-height: 95%;
  max-width: 420px;
  overflow-y: auto;
}

.main-interface-wrapper--dark {
  background: rgba(41, 41, 41, 0.95);
  color: rgb(224, 224, 224);
  font-weight: 300;
}

.title__main {
  color: inherit;
  text-align: center;
}
</style>
