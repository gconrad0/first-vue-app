<template>
    <h1>{{ newHere }}</h1>
</template>
<script>
    export default {
        name: 'CustomComp',
        props: {
            newHere: String
        }
    };
</script>
