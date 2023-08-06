<template>
    <div>
     <header>
         <nav>
             <ul>
                 <li><NuxtLink to="/products">Nuxt Merch</NuxtLink></li>
                 
             </ul>
         </nav>
     </header>
 </div>
 <div>
     <slot />
     <footer>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
     </footer>
 </div>
 </template>
 
 <script setup>
 
 </script>
 
 <style scoped>
     .router-link-active {
         color: teal;
     }
 </style>