<template>
    <h1>Home Page</h1>
    {{ $store.doubleCounter }}
</template>
<script setup>
const { $store } = useNuxtApp();
</script>