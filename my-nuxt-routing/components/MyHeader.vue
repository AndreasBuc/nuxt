<template>
  <div class="Header">
    <header>
      <ul class="nav-items">
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/users">User</nuxt-link>
        </li>
      </ul>
    </header>
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  name: 'MyHeader',
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
  // },
  // layout: ,
}
</script>

<style scoped>

.Header {
  width:100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #ccc;
  margin: 0;
}
.nav-items{
  list-style: none;
  padding: 0;
  margin: 0px 20px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 80%
}
.nav-items a{
  text-decoration: none;
  color: black;
}

.nav-items a:hover,
.nav-items a:active {
  color: white;
}
</style>
