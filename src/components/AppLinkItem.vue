<template>
    <div class="app-link-item">
        <img src="app-link-item__img" alt="">
        <div class="app-link-item__link text">
            GFqweqeq
        </div>
        <div class="app-link-item__block-stars">
            <div class="app-link-item__stars" v-for="arr in 5" :key="arr.id">
                1
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: "AppLinkItem",
    components: {
        
    }
}

</script>

<style scoped>

.app-link-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 190px;
    height: 165px;
    opacity: 0px;
    border: 2px solid #B8FF14;
}

.app-link-item__block-stars {
    display: flex;
    gap: 8px;
}

</style>