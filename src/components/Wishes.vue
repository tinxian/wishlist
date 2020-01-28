<template>
  <div>
    <div v-bind:key="wish.id" v-for="wish in wishes">
      <WishItem />
    </div>
  </div>
</template>

<script>
import WishItem from './WishItem.vue';

export default {
  name: "Wishes",
  components: {
    WishItem
  },
  props: ["wishes"]
}
</script>
<style scoped>

</style>
