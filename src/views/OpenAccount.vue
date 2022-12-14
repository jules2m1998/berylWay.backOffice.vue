<script setup lang="ts">
import { ref } from 'vue';

const test = ref<string>("Tester")
</script>

<template>
    <p>
        {{test}}
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam tempore, repellendus exercitationem ex fugit nulla, doloremque ipsa in aperiam asperiores maxime culpa nihil officia omnis, cumque vel natus? Sint, sapiente.
    </p>
</template>