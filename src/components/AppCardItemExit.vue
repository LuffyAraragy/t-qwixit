<template>
    <div class="app-card-item-exit">
        <div class="app-component-card__item">
            <div class="text-title">
                Вперед!
            </div>
            <div class="text">
                за покупками
            </div>
            <button class="button">
                Купить товар
            </button>
        </div>
    </div>
</template>

<script>

export default {
    name: "AppCardItemExit"
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
    justify-content: flex-end;
    gap: 24px;
    padding: 32px 40px 32px 40px;
    background-color: #1467FF;
    max-width: 384px;
    max-height: 428px;
    min-height: 428px;
    opacity: 0px;
}

</style>