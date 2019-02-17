<template>
  <section class="section page">
    <div class="container">
      <h3 class="title">title new page: ({{ this.$route.params.id }})</h3>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'MyPage',
    data() {
      return {

      }
    },

    watch: {
      '$route'(to, from) {
        this.getParams(to.params.id);
      }
    },

    created() {
      this.getParams(this.$route.params.id);
    },

    methods: {
      getParams(id) {
        console.log(`page id: (${id})`);
      }
    }
  }
</script>

<style scoped>
  .page {
    padding: 100px 0;
    background-color: brown;
  }
</style>