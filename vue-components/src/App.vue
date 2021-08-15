<template>
<div>
  <NameList>
    <template v-slot:default="slotProps">
      {{slotProps.firstName}} {{slotProps.lastName}}
    </template>
  </NameList>
  <NameList>
    <template v-slot:default="slotProps">
      {{slotProps.lastName}} {{slotProps.firstName}}
    </template>
  </NameList>
</div>
</template>

<script>
import NameList from './components/NameList.vue'

export default {
  name: 'App',
  components: {
    NameList
  },
  data() {
    return { 
      
    }
  },
  methods: {
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

img {
    max-width: 190px;
    height: auto
}

</style>
