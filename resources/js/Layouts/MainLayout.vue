<template>
    <main>
        <header class="flex gap-4">
          <Link href="/">Home</Link>
          <Link href="/about-us">About</Link>
          <Link href="/contact">Contact</Link>
        </header>

        <br>

        <article>
          <slot />  <!-- Content from the page will be injected here -->
        </article>
    </main>
</template>

<script setup>
  import { Link } from '@inertiajs/vue3';
</script>

