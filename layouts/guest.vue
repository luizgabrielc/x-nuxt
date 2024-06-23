<template>
  <ul class="bg-zinc-600 p-10 text-yellow-500">
    <li><NuxtLink href="/login">Login</NuxtLink></li>
    <li>
      <NuxtLink
        href="/register"
        prefetch
        >Register</NuxtLink
      >
    </li>
  </ul>
  <slot />
</template>

<script lang="ts"></script>

<style scoped></style>
