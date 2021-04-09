<template>
    <img class="heroImage" />
</template>

<script>

export default {
    name: 'HeroImage',
};
</script>

<style lang="scss" scoped>
    .heroImage {
        width: 100%;
        height: 100vh;
        background: lightblue;
        position: fixed;
        top: 0;
        z-index: -1;
    }
</style>
