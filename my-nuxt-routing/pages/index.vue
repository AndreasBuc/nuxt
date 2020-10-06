<template>
  <div>
    This is the Homepage
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  name: 'Main',
  props: {

  },
  components: {

  },
  data() {
    return {

    }
  },
  methods: {
    navigateToProducts() {
      this.$router.push('/products')
    }
  },
  // created() {
  //
  // },
  // computed: {
  //
  // },
  // destroyed() {
  //
  // },
  // deactivated() {
  //
  // },
  // activated() {
  //
  // },
  // beforeRouteEnter(to, from, next) {
  //
  //   return next(vm => {
  //
  //     });
  // },
  // beforeRouteUpdate (to, from, next) {
  // next();
  // },
  // beforeRouteLeave (to, from, next) {
  // next();
  // }
}
</script>

<style scoped>

</style>
