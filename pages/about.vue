<template>
  <div>
      <h1>About Bad Jokes</h1>
      <p>This is an app to show corny jokes</p>
  </div>
</template>

<script>
export default {
    head() {
        return {
            title: 'About the app',
            meta: [
                {
                    hid: 'about',
                    name: 'description of the app',
                    content: 'Best place for corny dad jokes'
                }
            ]
        }
    }
}
</script>

<style>

</style>