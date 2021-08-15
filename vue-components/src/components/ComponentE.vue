<template>
    <div>
        <h2>Component E</h2>
        <ComponentF />
    </div>
</template>

<script>
import ComponentF from './ComponentF'
    export default {
        name: 'ComponentE',
        components: {
            ComponentF,
        }
    }
</script>

<style scoped>

</style>