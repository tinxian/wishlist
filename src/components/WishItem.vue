<template>
  <div>
    <p>Wish Item</p>
  </div>
</template>

<script>
export default {
  name: "WishItem"
}
</script>

<style scoped>
  .wish-item {
    background: #f4f4f4;
    padding: 10px;
    border-bottom: 1px #ccc dotted;
  }
  .is-complete {
    text-decoration: line-through;
  }
  .del {
    background: #ff0000;
    color: #fff;
  }
</style>
