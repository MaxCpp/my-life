<script lang="ts">
import {defineComponent} from 'vue'

export default defineComponent({
    name: "default"
})
</script>

<template>
    <div class="app">
        <header class="header">
            <NuxtLink to="/">Main</NuxtLink>
            <NuxtLink to="/children">Children</NuxtLink>
            <NuxtLink to="/map">Map</NuxtLink>
        </header>
    
        <NuxtPage/>
    </div>
</template>

<style lang="scss" scoped>
.app {
    min-height: 100vh;
}

.header {
    display: flex;
    gap: 20px;
    height: 60px;
    padding: 20px;
}
</style>