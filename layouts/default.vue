<template>
    <section class="default-layout">

        <LayoutsSideBar />

        <menu class="menu">
            <slot />
        </menu>
    </section>
</template>

<script setup lang="ts">
console.log('Loaded');


</script>

<style scoped>
.default-layout {
    display: grid;
    grid-template-columns: 1fr 6fr;
}

</style>