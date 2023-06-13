<template>
    <div class="flex flex-col min-h-screen font-Roboto bg-weather-primary">
        <siteNavigation />
        <RouterView />
    </div>
</template>

<script setup>

import {RouterView} from "vue-router";
import siteNavigation from "./components/SiteNavigation.vue"

</script>

<style lang="scss" scoped>

</style>