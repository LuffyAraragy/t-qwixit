<template>
    <div class="main-page container">
        <AppComponent>
            <button class="button">
                О нас
            </button>
            <div class="block-content">
                <div class="text-title">
                    Маркетплейс оригинальных товаров из США QWIXIT – часть группы компания Pochtoy.com LLC
                </div>
                <div class="text-title">
                    Pochtoy.com LLC доставляет товары из США более 15 лет
                    и, помимо Qwixit, владеет еще двумя мейлфорвардинговыми компаниями
                </div>
            </div>
        </AppComponent>
        <!-- TODO добавить блок с картинками самый красивый -->
        <AppComponentLink>
            <div class="text-block">
                <div class="text-title">
                    prostobox.com
                </div>
            </div>
            <div class="controller-flex">
                <AppLinkItem v-for="arr in 3" :key="arr.id">

                </AppLinkItem>
            </div>
        </AppComponentLink>

        <AppComponent>
            <button class="button">
                Покупка
            </button>
            <div class="block-content">
                <div class="text-title">
                    Что надо знать до того, как совершить покупку
                    в гипермаркете американских товаров QWIXIT
                </div>
            </div>
        </AppComponent>

        <AppComponentCard>

        </AppComponentCard>
        
        <AppComponent>
            <button class="button">
                Большой склад
            </button>
            <div class="block-content">
                <div class="text-title">
                    Вы сможете отслеживать весь путь заказа в личном кабинете на нашем сайте, 
                    а также на любом сайте отслеживания, но только с момента пересечения товаром границы страны назначения.
                </div>
            </div>
        </AppComponent>

        <AppComponentPadding>
            <div class="text-title">
                О возвратах товаров
            </div>
            <div class="text">
                К сожалению, возврат товаров в американские магазины невозможен. 
                Срок возврата товаров в магазины США составляет не более 30 дней. 
                К сожалению, неподошедший товар просто не успеет дойти обратно, чтобы
                мы успели осуществить его возврат.
            </div>
            <div class="text">
                Для пристройки неподошедщих товаров мы создали этот чат в телеграме. Здесь вы сможете продать любые неподошедшие вам товары при необходимости.
            </div>
        </AppComponentPadding>

        <!-- TODO добавить блок с человечком -->
        <TheAppImageContent>
            
        </TheAppImageContent>

        <AppComponentPadding>
            <div class="text-title">
                О возвратах товаров
            </div>
            <div class="text">
                К сожалению, возврат товаров в американские магазины невозможен. 
                Срок возврата товаров в магазины США составляет не более 30 дней. 
                К сожалению, неподошедший товар просто не успеет дойти обратно, чтобы
                мы успели осуществить его возврат.
            </div>
            <div class="text">
                Для пристройки неподошедщих товаров мы создали этот чат в телеграме. Здесь вы сможете продать любые неподошедшие вам товары при необходимости.
            </div>
        </AppComponentPadding>

        <AppComponent>
            <button class="button">
                Купить
            </button>
            <div class="block-content">
                <div class="text-title">
                    Вы сможете отслеживать весь путь заказа в личном кабинете на нашем сайте, 
                    а также на любом сайте отслеживания, но только с момента пересечения товаром границы страны назначения.
                </div>
                <div class="text">
                    Если стоимость товара или заказа свыше 1000 евро, то пошлина начисляется по формуле: 
                    (стоимость товаров в посылке минус 1000 евро)*1,15 + фиксированный таможенный сбор 500р., 
                    а также 3%комиссии от суммы размера комиссии и фиксированного сбора
                </div>
            </div>
        </AppComponent>

        <AppComponentPadding>
            <div class="block-content">
                <div class="text-title">
                    Вы сможете отслеживать весь путь заказа в личном кабинете на нашем сайте, 
                    а также на любом сайте отслеживания, но только с момента пересечения товаром границы страны назначения.
                </div>
                <div class="text">
                    Если стоимость товара или заказа свыше 1000 евро, то пошлина начисляется по формуле: 
                    (стоимость товаров в посылке минус 1000 евро)*1,15 + фиксированный таможенный сбор 500р., 
                    а также 3%комиссии от суммы размера комиссии и фиксированного сбора
                </div>
            </div>
        </AppComponentPadding>

        <!-- TODO карточки банка -->

        <div class="block-technical-support">
            <img src="" alt="">
            <div class="text">
                Ищите что-то или хотите уточнить как мы работаем? 
                Наша профессиональная служба ответит вам в чате. 
                Чат можно найти в правом нижнем углу этого сайта. 
                Просто нажмите на <span class="text text--green">зеленый блок</span> внизу страницы и начните диалог с оператором!
            </div>
        </div>
    </div>
</template>

<script>
import AppComponentPadding from '@/components/AppComponentPadding.vue'
import AppComponent from '@/components/AppComponent.vue'
import AppComponentCard from '@/components/AppComponentCard.vue'
import AppComponentLink from '@/components/AppComponentLink.vue'
import AppLinkItem from '@/components/AppLinkItem.vue'
import TheAppImageContent from '@/components/TheAppImageContent.vue'


export default {
    name: "MainPage",
    components: {
        AppComponentPadding,
        AppComponent,
        AppComponentCard,
        AppComponentLink,
        AppLinkItem,
        TheAppImageContent
    }
}

</script>

<style scoped>
.controller-flex {
    display: flex;
    gap: 12px;
}

.text-block {
    margin-bottom: 40px;
    display: flex;
    gap: 25px;
    align-items: center;
}
</style>