<script setup></script>

<template>
    <header class="bg-slate-800 text-white">
        <nav class="p-6 mx-auto max-w-screen-lg">
            <Link :href="route('home')">Home</Link>
        </nav>
    </header>

    <main class="p-6">
        <slot />
    </main>
</template>
