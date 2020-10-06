<template>
  <div class="prod">
    This is Product: {{$route.params.pid}}
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  name: 'prod',
  props: {

  },
  components: {

  },
  data() {
    return {

    }
  },
  methods: {

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
