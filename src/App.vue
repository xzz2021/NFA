<script setup lang="ts">
import Home from "./views/home.vue"
import Main from "./views/Main.vue"
</script>

<template>
    <Home >
        <template v-slot:main>
            <Main />
        </template>
    </Home>
</template>

<style scoped>

</style>
