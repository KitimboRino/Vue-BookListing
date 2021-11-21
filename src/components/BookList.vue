<template>
  <div>
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: "BookList",
  data: function() {
    return{
    title: "All books"
    }
  },
};
</script>

<style scoped>
h1 {
font-weight: normal;
}
</style>