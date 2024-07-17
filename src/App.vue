<template>
  <StoredResources :resources="storedResources"></StoredResources>
</template>

<script>
  import StoredResources from './components/learning-resources/StoredResources.vue';
  export default {
    components: {
      StoredResources
    },
    data() {
      return {
        storedResources: [
          {
            id: 123,
            title: "udemy Course",
            description: "Courses learning platform..",
            link: "https://www.udemy.com"
          },
          {
            id: 456,
            title: "Google Web",
            description: "Search Enginer",
            link: "https://www.google.com"
          }
        ]
      }
    }
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>

