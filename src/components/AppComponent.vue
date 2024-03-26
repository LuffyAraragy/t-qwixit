<template>
    <div class="app-component">
        <slot>

        </slot>
    </div>
</template>

<script>

export default {
    name: "AppComponent",
    components: {
        
    }
}

</script>

<style scoped>
.app-component {
    max-width: 1150px;
    margin: 40px 0;
    display: flex;
    gap: 40px;
}
</style>