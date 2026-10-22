<template>
    <h1>Hello My vue component</h1>
    <button @click="logMessage()">Click Here</button>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'MyComponent',
    props: {  
    },
    methods: {
        logMessage() {
            console.log('My vue component sample!');
        }
    },
    setup() {
      // Composition API logic can go here
    },
});
</script>
