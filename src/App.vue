<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
    <div>
        <h1 class="text-cyan-500 text-3xl font-bold underline">Hello world!</h1>
    </div>
    <HelloWorld msg="Vite + Vue" />

    <div className="p-4">
        <p className="p-4">aqua theme</p>

        <button className="btn">Button</button>
        <button className="btn btn-neutral">Neutral</button>
        <button className="btn btn-primary">Primary</button>
        <button className="btn btn-secondary">Secondary</button>
        <button className="btn btn-accent">Accent</button>
        <button className="btn btn-ghost">Ghost</button>
        <button className="btn btn-link">Link</button>
    </div>
</template>

<style></style>
