<template>
    <div>
        <button class="NuxtLink" @click="goTo('/')">前往 Home</button>
        <NuxtLink class="NuxtLink" to="/about">前往 About</NuxtLink>
        <NuxtLink class="NuxtLink" to="/about/about-1">前往 About1</NuxtLink>
        <NuxtLink class="NuxtLink" to="/about/about-2">前往 About2</NuxtLink>
    </div>
</template>
<style>
.NuxtLink {
  margin-right: 20px;
}
</style>
<script>
export default {
    methods: {
        goTo(path) {
            this.$router.push(path)
        }
    }
}
</script>