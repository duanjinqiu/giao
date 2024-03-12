<template>
    <div>
        我是Home.vue组件
        <div>
            <input type="text" v-model="msg">
        </div>
        <p>
            {{ msg }}
        </p>
    </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const msg = ref('Hello World!');
</script>