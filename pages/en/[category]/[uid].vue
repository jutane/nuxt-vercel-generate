<template>
    <div :class="route.name">
        {{ route.params.uid }}
    </div>
</template>

<script setup>
const route = useRoute()
</script>
