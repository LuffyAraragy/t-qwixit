<template>
    <div class="app-component-card">
        <!-- <div class="app-component-card__item">
            <div class="app-component-card__circle">
                <div class="app-component-card__text text">
                    1
                </div>
            </div>
            <div class="text">
                Чтобы заказать товар вам не надо разбираться в тонкостях покупок за рубежом.
            </div>
        </div> -->
        <slot>
            <AppCardItem v-for="arr in 5" :key="arr.id">

            </AppCardItem>
            <AppCardItemExit>
                
            </AppCardItemExit>
        </slot>
    </div>
</template>
<script>
import AppCardItem from './AppCardItem.vue'
import AppCardItemExit from './AppCardItemExit.vue'

export default {
    name: "AppComponentCard",
    components: {
        AppCardItem,
        AppCardItemExit
    }
}

</script>

<style scoped>

.app-component-card {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
}





</style>