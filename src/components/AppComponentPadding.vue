<template>
    <div class="app-component-padding">
        <slot>
            
        </slot>
    </div>
</template>

<script>

export default {
    name: "AppComponentPadding",
    components: {

    }
}

</script>

<style scoped>

.app-component-padding {
    margin: 40px 0;
    padding: 32px;
    display: grid;
    gap: 32px;
    background-color: #1467FF;
}

</style>