<template>
  <div>
    <form class="" action="#" method="post" @submit="bookSubmit">
      <input type="text" name="title" value="" placeholder="Book Title" />
      <input type="text" name="author" value="" placeholder="Book Author" />
      <button type="submit" name="button">Add Book</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "BookForm",
  props: ["books"],
  data() {
    return {
      bookTitle: "",
      bookAuthor: "",
    };
  },
};
</script>

<style lang="scss" scoped>
</style>