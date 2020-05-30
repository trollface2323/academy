<template>
    <div class="main">
        <section class="header">
            <div class="header__photo">
                <img src="../photo/Path 21.svg" alt="">
                <img src="../photo/Ellipse 1.svg" alt="">
            </div>  <!--желтая хрень в углу edir-->

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
            <!--            <div class="choose__body">-->
            <div class="choose__title">Выберите направление</div>

            <div class="choose__box">
<!--                todo при наведении на карточку, она немного смещается вбок,
                      адекватно не смог решить эту проблему, при нажатии цвет тоже не
                      фиксируется
                      -->
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
        <section class="reg">
            <div class="reg__title">Театральная искусство</div>
            <div class="reg__body">
                <div class="reg__item">
                    <div class="reg__item-title">Какая-то сфера</div>
                    <div class="reg__item-btn">
                        <a href="#">Регистрация</a>
                    </div>
                </div>
                <div class="reg__item">
                    <div class="reg__item-title">Какая-то сфера2</div>
                    <div class="reg__item-btn">
                        <a href="#">Регистрация</a>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        name: "Choose"
    }
</script>

<style scoped lang="scss">

    /*@import url(../css/stylesheet.css); скачал файлы со шрифтами, пробовал их сюда добавить, не работает*/

    .main {
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


        &__card{
            display: inline-block;
            box-shadow: 0 10px 20px #00000029;
            width: 378px;
            height: 434px;
            position: relative;
            text-align: center;
            border-radius: 20px;
            margin: 58px 29px 60px 0;
            &:hover{
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
    .reg{
        color: #393939;
        &__title{
            text-align: left;
            font-size: 50px;
            font-weight: 600;
            margin-bottom: 30px;
        }
        &__body{

        }
        &__item{
            display: flex;
            align-items: center;
            text-align: left;
            box-shadow: 0 5px 20px #00000029;
            border-radius: 20px;
            margin-bottom: 30px;
            height: 150px;
            padding-left: 52px;
            &-title{
                font-size: 40px;
                
            }
            &-btn{
                font-size: 31px;
                background: #FFA358 0 0 no-repeat padding-box;
                box-shadow: 0 3px 6px #00000029;
                border-radius: 20px;
                padding: 25px 19px;
                margin: 0 18px 0 auto;

                & a{
                    text-decoration: none;
                    color: #fff;
                }
            }
        }
    }


</style>