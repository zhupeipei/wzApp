<template>
  <div>
  </div>
</template>
<script>
  export default {
    beforeCreate() {
      console.log("test create");
//      cordova.exec(null, null, "ActionFromJsToNative", "showExternalWebsite", ["https://vux.li/demos/v2/?x-page=v2-doc-home#/"]);
    },
    beforeMount() {
      console.log("test mount");
    },
    data() {
      return {
      }
    },
    methods: {}
  }
</script>
<style></style>
