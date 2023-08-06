<template>
   <div>
    <header>
        <nav>
            <ul>
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/products">Products</NuxtLink></li>
            </ul>
        </nav>
    </header>
</div>
<div>
    <slot />
</div>
</template>

<script setup>

</script>

<style scoped>
    .router-link-active {
        color: teal;
    }
</style>