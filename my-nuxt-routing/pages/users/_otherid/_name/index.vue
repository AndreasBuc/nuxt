<template>
  <div class="withName">
    <p>And here the id: {{$route.params.otherid}}</p>
    <p>And here the name: {{$route.params.name}}</p>
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
  layout:'default',
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
