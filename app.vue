<template>
  <div>
    <h1>Welcome</h1>
    <NuxtLink class="NuxtLink" to="/">前往 Home</NuxtLink>
    <NuxtLink class="NuxtLink" to="/about">前往 About</NuxtLink>
    <NuxtLink class="NuxtLink" to="/about/about-1">前往 About1</NuxtLink>
    <NuxtLink class="NuxtLink" to="/about/about-2">前往 About2</NuxtLink>
    <NuxtPage />
  </div>
</template>
<style>
.NuxtLink{
  margin-right: 20px;
}
</style>