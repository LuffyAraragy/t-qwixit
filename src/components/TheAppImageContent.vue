<template>
    <div class="the-app-image-content">
        <div class="the-app-image-content__block-img">
            <img src="@/assets/51.png" alt="" class="img">
        </div>
        <div class="the-app-image-content__block-content">
            <div class="the-app-image-content__title text-title">
                До 1 апреля 2024
            </div>
            <div class="the-app-image-content__text text-title">
                сумма беспошлинного ввоза в Россию, Казахстан и Беларусь составляет 1000 евро на одну посылку.
            </div>
            <!-- Чёрточка -->
            <div class="the-app-image-content__text text">
                Если товар, который вы покупаете, стоит дороже
                <span>1 000 евро,</span>
                то пошлина уже включена в стоимость товара.
            </div>
            
        </div>
    </div>
</template>
<script>

export default {
    name: "TheAppImageContent"
}

</script>

<style scoped>

.img {
    /* width: 400px;
    height: 400px; */
    position: absolute;
    left: -62px;
    top: -85px;
}

.the-app-image-content__block-img {
    position: relative;
    width: 400px;
}

.the-app-image-content {
    width: 1150px;
    height: 426px;
    gap: 0px;
    opacity: 0px;
    background: linear-gradient(153.43deg, #96979D 0%, #7F8595 41.67%, #ADAEB6 83.33%);
}
    
</style>