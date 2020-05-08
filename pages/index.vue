<template>
  <div class="container2">
    <h2>Welcome to the best Bad jokes in the web</h2>
  </div>
</template>

<script>

export default {
    head() {
        return {
            title: 'Bad jokes',
            meta: [
                {
                    hid: 'home',
                    name: 'home',
                    content: 'Best place for corny dad jokes'
                }
            ]
        }
    },
  components: {
  }
}
</script>

<style>
.container2 {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
