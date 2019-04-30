<template lang="pug">
  #rootc
    main-interface
    app-map
</template>

<script>
export default {
  components: {
    mainInterface: () => import("@/main-interface/mainInterface.vue"),
    appMap: () => import("@/map/appMap.vue")
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&amp;subset=cyrillic");
@import url("https://use.fontawesome.com/releases/v5.7.2/css/all.css");

body {
  margin: 0;
  padding: 0;
  font-family: "Open Sans", sans-serif;
  font-size: 15px;
  overflow: hidden;
  background: rgb(51, 50, 49);
}

h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
  font-weight: normal;
}

ul {
  padding: 0;
  margin: 0;
  list-style: none;
}

::-webkit-scrollbar {
  display: none;
}

#root {
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}
</style>
