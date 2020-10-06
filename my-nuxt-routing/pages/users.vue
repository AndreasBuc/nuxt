<template>
  <div class="NestedUsers">
    <div>
      <input type="number" v-model="userID" name="" value="">
      <button type="button" @click="onLoadUser" name="button"> Load 1</button>

      <input type="text" v-model="userName" name="" value="">
      <button type="button" @click="onLoadUserName" name="button"> Load 2</button>
      <nuxt-child></nuxt-child>
    </div>
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  name: 'NestedUsers',
  props: {

  },
  components: {

  },
  data() {
    return {
      userID: 0,
      userName: '',
    }
  },
  methods: {
    onLoadUser() {
      this.$router.push({name: 'users-otherid', params: {otherid: this.userID}})
    },
    onLoadUserName() {
      this.$router.push({name: 'users-otherid-name', params: {otherid: this.userID, name: this.userName}})
    }
  },
  layout:'users',
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
