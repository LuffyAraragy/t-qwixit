<template>
    <div class="app-card-item">
        <div class="app-component-card__item">
            <div class="app-component-card__circle">
                <div class="app-component-card__text text">
                    1
                </div>
            </div>
            <div class="text">
                Чтобы заказать товар вам не надо разбираться в тонкостях покупок за рубежом.
            </div>
        </div>
    </div>
</template>
<script>

export default {
    name: "AppCardItem",
    components: {

    }
}

</script>

<style scoped>
.app-component-card__text {
    font-size: 24px;
    font-weight: 400;
    line-height: 40px;
}

.app-component-card__item {
    display: flex;
    flex-direction: column;
    gap: 24px;
    padding: 32px 40px 32px 40px;
    background-color: #1467FF1A;
    max-width: 384px;
    max-height: 428px;
    min-height: 428px;
    opacity: 0px;

}

.app-component-card__circle {
    width: 100px;
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #ffffff;
    border-radius: 50%;
}
</style>