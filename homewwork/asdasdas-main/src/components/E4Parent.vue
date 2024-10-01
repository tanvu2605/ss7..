<template>
    <div>
        {{ count }}
        <E4Child @increment="handle" />
    </div>
</template>
<script setup>
import { ref } from 'vue';
import E4Child from './E4Child.vue';

const count = ref("")
const handle = () => {
    count.value++
}
</script>
<style></style>