<template>
    <section class="reg">
        <div class="reg__btn">
            <button type="submit"><span>Регистарция</span></button>
        </div>
        <div class="point">
            <span>тут знак вопроса</span>
        </div>
        <div class="reg__title">Регистрация</div>
            <img src="../photo/user.svg" alt="" class="icons__item">
        <div class="reg__body">
            <div class="reg__form">
                <form action="">
                    <input type="text" placeholder="ФИО ребенка" class="reg__form-item"><img src="../photo/user.svg" alt="" class="icons__item">
                    <input type="number" placeholder="Возраст ребенка" class="reg__form-item"><img src="../photo/user.svg" alt="" class="icons__item">
                    <input type="text" placeholder="ФИО родителя" class="reg__form-item"><img src="../photo/user.svg" alt="" class="icons__item">
                    <input type="number" placeholder="Телефон" class="reg__form-item"><img src="../photo/user.svg" alt="" class="icons__item">                    <input type="text" placeholder="Почта" class="reg__form-item">
                    <div class="agree">
                        <input type="checkbox" class="checkbox" id="yes"><label for="yes"><span> согласие на обработку персональных данных</span></label>
                    </div>

                </form>
            </div>
            <div class="reg__text">
                <div class="reg__text-title">Мультимедийный театр «Сфера»</div>
                <div class="reg__text-sub-title">Мультимедийный Театр «Сфера» - это видео перформанс будущего, который открывает безграничные возможности в представлениях, включает в себя взаимодействие реальных актёров, находящихся в зоне сценического пространства с графическими объектами, что несомненно потрясает даже самых искушенных зрителей. Отличительная особенность программы заключается в разнообразии содержания программы, что позволяет создавать собственные проекты, театральные представления, перформансы, научно-популярные фильмы и другие тематические мероприятия.</div>
                <div class="reg__text-footer">􀎫 Наб.реки Малой Невки, д.1А</div>
            </div>
        </div>

    </section>
</template>

<script>
    export default {
        name: "Reg"
    }
</script>

<style scoped lang="scss">



</style>