<template>
  <div>
    <li>{{book.title}}:{{book.author}}</li>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        name: 'BookItem',
        props: ['book']
      }
    },
  }
</script>

<style lang="scss" scoped>
li {
  display: block;
  margin: 0 10px;
}
</style>