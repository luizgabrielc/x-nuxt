<template>
    <div>
        <ul class="bg-zinc-600 p-10 text-yellow-500">
            <li><NuxtLink href="/">Home</NuxtLink></li>
            <li><NuxtLink href="/about" prefetch>About</NuxtLink></li>
        </ul>
        <slot/>
    </div>
</template>

<script lang="ts">
</script>

<style scoped>

</style>