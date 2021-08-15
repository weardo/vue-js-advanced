<template>
<div>
  <!-- <Greet name="Bruce" heroName="Batman" />
  <Greet name="Clark" heroName="Superman" />
  <Greet name="Diana" heroName="Wonder Woman" />
  <Greet :name="name" :heroName="channel" /> -->

  <Article id="my-article" title="Article Title" :likes="50" :isPublished="true" />
</div>
</template>

<script>
// import Greet from './components/Greet'
import Article from './components/Article'

export default {
  name: 'App',
  components: {
    // Greet,
    Article
  },
  data() {
    return {
      name: 'Abhishek',
      channel: 'Weardo'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
