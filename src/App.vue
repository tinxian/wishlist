<template>
  <div id="app">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {

  },
  data() {
    return {
      wishes: [
        {
          id: 1,
          title: 'Wish 1',
          completed: false
        },
        {
          id: 2,
          title: 'Wish 2',
          completed: false
        },
        {
          id: 3,
          title: 'Wish 3',
          completed: false
        }
      ]
    }
  }
}
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  line-height: 1,4;
}
</style>
