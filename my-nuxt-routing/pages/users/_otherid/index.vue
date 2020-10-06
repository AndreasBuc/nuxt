<template>
  <div class="otherID">
    some other ID: {{$route.params.otherid}}
  </div>
</template>

<script>
// import  from "@/components/"
export default {
  validate(data) {
    console.log(data);
    return !isNaN(data.params.otherid)
  }
}
</script>

<style scoped>

</style>
