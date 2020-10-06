<template>
  <div class="withName">
    And here the id: {{$route.params.otherid}}
    And here the name: {{$route.params.name}}
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  name: 'withName',
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
