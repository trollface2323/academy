<template>
    <div class="main">
        <section class="header">
            <div class="header__photo">
                <img src="../photo/Path 21.svg" alt="">
                <img src="../photo/Ellipse 1.svg" alt="">
            </div>

            <div class="header__icon">
                <img src="../photo/Group 34.svg" alt="">
            </div>
            <div class="header__title"> Регистраци на программы</div>
            <div class="header__sub-title">Данная заявка НЕ гарантирует зачисление на выбранные программы. Окончательные
                списки формируются на основании письменного заявления от родителей или законных представителей. Наши
                администраторы свяжутся с вами для уточнения деталей.
            </div>
        </section>

        <section class="choose">
            <div class="choose__title">Выберите направление</div>
            <div class="choose__box">
                <div class="choose__card">
                    <input type="checkbox" id="1" class="checkbox">
                    <label for="1">
                        <div class="choose__box-photo">
                            <img src="../photo/Group 39.svg" alt="" class="">
                        </div>
                        <span>Театральное искусство</span>
                    </label>
                </div>
                <div class="choose__card">
                    <input type="checkbox" id="2" class="checkbox">
                    <label for="2">
                        <div class="choose__box-photo">
                            <img src="../photo/Group 39.svg" alt="">
                        </div>
                        <span class="">Театральное искусство</span>
                    </label>
                </div>
            </div>
            <div class="choose__old">
                <div class="choose__old-title">Выберите возраст</div>
                <div class="choose__old-number">

                    <input id="5" type="radio" name="old" class="checkbox"><label
                        for="5"><span>5</span></label>
                    <input id="6" type="radio" name="old" class="checkbox"><label for="6"><span>6</span></label>
                    <input id="7" type="radio" name="old" class="checkbox"><label for="7"><span>7</span></label>
                    <input id="8" type="radio" name="old" class="checkbox"><label for="8"><span>8</span></label>
                    <input id="9" type="radio" name="old" class="checkbox"><label for="9"><span>9</span></label>
                    <input id="10" type="radio" name="old" class="checkbox"><label for="10"><span>10</span></label>
                    <input id="11" type="radio" name="old" class="checkbox"><label for="11"><span>11</span></label>
                    <input id="12" type="radio" name="old" class="checkbox"><label for="12"><span>12</span></label>
                    <input id="13" type="radio" name="old" class="checkbox"><label for="13"><span>13</span></label>
                    <input id="14" type="radio" name="old" class="checkbox"><label for="14"><span>14</span></label>
                    <input id="15" type="radio" name="old" class="checkbox"><label for="15"><span>15</span></label>
                    <input id="16" type="radio" name="old" class="checkbox"><label for="16"><span>16</span></label>
                    <input id="17" type="radio" name="old" class="checkbox"><label for="17"><span>17</span></label>

                </div>
            </div>
        </section>
        <section class="course">
            <div class="course__title">Театральная искусство</div>
            <div class="course__body">
                <div class="course__item">
                    <div class="course__item-title">Какая-то сфера</div>
                    <div class="course__item-btn">
                        <a href="#" data-toggle="modal" data-target="#reg">Регистрация</a>
                    </div>
                </div>
                <div class="course__item">
                    <div class="course__item-title">Какая-то сфера2</div>
                    <div class="course__item-btn">
                        <a href="#">Регистрация</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Modal -->
        <div class="modal fade" id="reg" data-backdrop="static" tabindex="-1" role="dialog"
             aria-labelledby="staticBackdropLabel" aria-hidden="true">
            <div class="modal-dialog" role="document">
                <div class="modal-content">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                    <div class="modal-body">

                        <div class="reg__btn">
                            <button type="submit"><span>Регистарция</span></button>
                        </div>

                        <div class="reg__title">Регистрация</div>
                        <img src="../photo/user.svg" alt="" class="icons__item">
                        <div class="reg__body">
                            <div class="reg__form">
                                <form action="">
                                    <input type="text" placeholder="ФИО ребенка" class="reg__form-item"><img
                                        src="../photo/user.svg" alt="" class="icons__item">
                                    <input type="number" placeholder="Возраст ребенка" class="reg__form-item"><img
                                        src="../photo/user.svg" alt="" class="icons__item">
                                    <input type="text" placeholder="ФИО родителя" class="reg__form-item"><img
                                        src="../photo/user.svg" alt="" class="icons__item">
                                    <input type="number" placeholder="Телефон" class="reg__form-item"><img
                                        src="../photo/user.svg" alt="" class="icons__item"> <input type="text"
                                                                                                   placeholder="Почта"
                                                                                                   class="reg__form-item">
                                    <div class="agree d-flex">
                                        <input type="checkbox" class="reg__checkbox" id="yes"><label for="yes"><span> согласие на обработку персональных данных</span></label>
                                    </div>

                                </form>
                            </div>
                            <div class="reg__text">
                                <div class="reg__text-title">Мультимедийный театр «Сфера»</div>
                                <div class="reg__text-sub-title">Мультимедийный Театр «Сфера» - это видео перформанс
                                    будущего, который открывает безграничные возможности в представлениях, включает в
                                    себя взаимодействие реальных актёров, находящихся в зоне сценического пространства с
                                    графическими объектами, что несомненно потрясает даже самых искушенных зрителей.
                                    Отличительная особенность программы заключается в разнообразии содержания программы,
                                    что позволяет создавать собственные проекты, театральные представления, перформансы,
                                    научно-популярные фильмы и другие тематические мероприятия.
                                </div>
                                <div class="reg__text-footer">􀎫 Наб.реки Малой Невки, д.1А</div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Choose"
    }
</script>

<style scoped lang="scss">

    /*@import url(../css/stylesheet.css);  todo скачал файлы со шрифтами, пробовал их сюда добавить, не работает*/

    .main {
        position: relative;
        width: 1920px;
        margin: 0 auto;
        padding: 0 150px;
        font-family: 'Muller', sans-serif;
    }

    .header {
        text-align: left;

        &__photo {
            position: absolute;
            top: 0;
            right: 0;
            width: 1064px;
            height: 780px;

            & img:last-child {
                position: absolute;
                top: 603px;
                right: 486px;
            }
        }

        &__icon {
            width: 201px;
            height: 113px;
            margin-top: 51px;
        }

        &__title {

            font-size: 70px;
            color: #393939;
            width: 574px;
            height: 150px;
            line-height: 80px;
            font-weight: 700;
            margin-top: 145px;

        }

        &__sub-title {
            margin-top: 45px;
            width: 799px;
            height: 248px;
            font-size: 30px;
            line-height: 33px;
            color: #393939;

        }
    }

    .choose {

        &__title {
            font-size: 80px;
            margin-top: 213px;
            font-weight: 300;
            color: #393939;
        }


        &__card {
            display: inline-block;
            box-shadow: 0 10px 20px #00000029;
            width: 378px;
            height: 434px;
            position: relative;
            text-align: center;
            border-radius: 20px;
            margin: 58px 29px 60px 0;

            &:hover {
                border: red solid 2px;
                margin-top: 1px;

            }
        }


        &__box {
            text-align: left;
            font-size: 31px;

            &-photo {
                padding-top: 102px;
                padding-bottom: 111px;
            }

            .checkbox {
                display: none;
            }

        }

        &__old {
            &-title {
                margin: 0 auto;
                font-size: 80px;
                color: #393939;
                padding-top: 30px;

            }

            &-number {
                margin: 37px 0 101px 0;
                font-size: 55px;

                & span {
                    position: relative;
                    margin-right: 42px;

                }

                & span:before {
                    content: '';
                    position: absolute;
                    width: 65px;
                    height: 65px;
                    top: 50%;
                    left: 50%;
                    border-radius: 50%;
                    transform: translate(-50%, -50%);
                    z-index: -1;

                }

                & span:hover:before {
                    background: yellow;
                }

                & input:checked + label span:before {
                    background: yellow;
                }

                .checkbox {
                    display: none;
                }

            }
        }
    }

    .course {
        color: #393939;

        &__title {
            text-align: left;
            font-size: 50px;
            font-weight: 600;
            margin-bottom: 30px;
        }

        &__body {

        }

        &__item {
            display: flex;
            align-items: center;
            text-align: left;
            box-shadow: 0 5px 20px #00000029;
            border-radius: 20px;
            margin-bottom: 30px;
            height: 150px;
            padding-left: 52px;

            &-title {
                font-size: 40px;

            }

            &-btn {
                font-size: 31px;
                background: #FFA358 0 0 no-repeat padding-box;
                box-shadow: 0 3px 6px #00000029;
                border-radius: 20px;
                padding: 25px 19px;
                margin: 0 18px 0 auto;

                & a {
                    text-decoration: none;
                    color: #fff;
                }
            }
        }
    }

    .reg {

        /*color: #393939;*/
        /*box-shadow: 0 10px 20px #00000029;*/
        /*padding-left: 45px;*/
        /*height: 847px;*/

        &__btn {
            position: absolute;
            left: 50%;
            bottom: -280px;
            box-shadow: 0 3px 6px #00000029;
            z-index: 2;
            border-radius: 20px;


            & button {
                background: #F8DD69;
                border-radius: 20px;
                width: 260px;
                height: 80px;


            }

            & span {
                font-size: 31px;
                color: #393939;
                padding: 25px 35px;
            }
        }

        &__title {
            font-size: 50px;
            font-weight: 700;
            margin-bottom: 112px;
            padding-top: 45px;
        }

        &__body {
            display: flex;
        }

        &__form {
            &-item {
                display: block;
                border: none;
                border-bottom: 1px gray solid;
                margin-bottom: 60px;
                font-size: 28px;
                width: 610px;
            }
        }

        &__text {
            padding-left: 150px;
            width: 605px;

            &-title {
                white-space: nowrap;
                text-align: left;
                font-size: 30px;
                font-weight: 700;
                margin-bottom: 40px;
            }

            &-sub-title {
                text-align: left;
                font-size: 22px;
                font-weight: 700;
                margin-bottom: 50px;
                line-height: 1em;
                width: 605px;
            }

            &-footer {
                font-size: 30px;
                font-weight: 700;
            }
        }

        .checkbox {
            width: 30px;
            height: 30px;
            font-size: 22px;
            margin-right: 20px;
        }
    }

    .agree {

        & input{
            width: 30px;
            height: 30px;
        }
        & span{
            margin-left: 15px;
            font-size: 22px;
        }

    }


    .icons__item {
        position: absolute;
        left: 630px;

    }
    .close{
        position: absolute;
        right: 40px;
        top: 20px;
        font-size: 40px;
        z-index: 2;
    }

    .modal-dialog {
        max-width: 87%;

    }

    .modal-body {
        padding-left: 45px;
        text-align: left;
    }


</style>