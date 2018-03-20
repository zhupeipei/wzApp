<template>
  <div>
    <page-header :title="title"></page-header>
    <div style="margin-top: 44px;">
      home
    </div>
  </div>
</template>
<script>
  import PageHeader from '../vendor/common/PageHeader.vue';
  export default {
    components: {
      PageHeader
    },
    data() {
      return {
        title: "首页"
      }
    },
    methods: {}
  }
</script>
<style></style>
