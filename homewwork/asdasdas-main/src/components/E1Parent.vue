<template>
    <div>
        <E1Child :name="props1"></E1Child>
    </div>
</template>

<script setup>
    import { ref } from 'vue';
    import E1Child from './E1Child.vue';

    const props1 = ref("rikkei academy");
</script>

<style scoped>
</style>