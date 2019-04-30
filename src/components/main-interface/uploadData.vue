<template lang="pug">
  .row.upload-data
    .col-lg-12
      h6.step-title.step-title--dark Data uploading
      .upload-data__content
        p.upload-data__text Upload a .csv file (comma separated) with cargo flows data
        form.upload-data__form(@submit.prevent="")
          .form-group.upload-data__form-group
            app-input(
              type="file"
              classArray="form-control-file"
              name="CSVGoods"
              inputId="inputGoodsTable"
            )
          app-button(
            type="submit"
            classArray="btn btn-dark"
            btnId="btn-submit"
            text="Submit"
          )
</template>

<script>
export default {
  components: {
    appInput: () => import("@/common/appInput"),
    appButton: () => import("@/common/appButton")
  }
};
</script>

<style lang="scss">
@import "styles/step-title.scss";

</style>
