<template>
    <main class="main">
        <div class="main__block">
            <h1 class="headline">Lorem Ipsum используют один и тот же текст</h1>
            <p class="subtitle">Он использует словарь из более чем 200 латинских слов, а также набор моделей предложений
            </p>
            <a @click="openModal" class="js-form-call" href="javascript:void(0);">Оставить заявку</a>
        </div>
        <div class="main__block">
            <img alt="picture" src="../assets/bg.png">
        </div>
        <div class="main__block">
            <div class="description">
                <div class="description__text">
                    Есть много вариантов Lorem Ipsum, но большинство из них имеет не всегда приемлемые модификации,
                    например, юмористические вставки или слова, которые даже отдалённо не напоминают латынь.
                </div>
                <div class="description__elem">
                    <p>2012</p>
                    <p>Lorem Ipsum</p>
                </div>
                <div class="description__elem">
                    <p>93</p>
                    <p>Приемлемые</p>
                </div>
                <div class="description__elem">
                    <p>150+</p>
                    <p>Набор моделей предложений</p>
                </div>
            </div>
        </div>
    </main>
    <div class="modal">
        <div class="modal__top">
            <a class="modal-logo" href="javascript:void(0);">
                <svg width="122" height="34" viewBox="0 0 122 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_280_604)">
                        <path
                            d="M68.0653 4.32086V9.08289H58.0987V14.2273H65.5563V18.8503H58.0987V28.7219H52.1396V4.32086H68.0653Z"
                            fill="white" />
                        <path d="M77.1564 3V28.7219H71.1973V3H77.1564Z" fill="white" />
                        <path
                            d="M99.8051 18.7112C99.8051 19.2674 99.7703 19.8467 99.7006 20.4492H86.2143C86.3072 21.6542 86.6905 22.5811 87.3643 23.2299C88.0612 23.8556 88.9092 24.1684 89.9082 24.1684C91.395 24.1684 92.4289 23.5428 93.0097 22.2914H99.3521C99.0268 23.566 98.4344 24.713 97.5748 25.7326C96.7385 26.7522 95.6814 27.5517 94.4036 28.131C93.1258 28.7103 91.6971 29 90.1173 29C88.2122 29 86.5163 28.5945 85.0294 27.7834C83.5425 26.9724 82.3809 25.8137 81.5446 24.3075C80.7082 22.8012 80.29 21.0401 80.29 19.0241C80.29 17.008 80.6966 15.2469 81.5097 13.7406C82.3461 12.2344 83.5077 11.0758 84.9946 10.2647C86.4814 9.45365 88.189 9.04813 90.1173 9.04813C91.9991 9.04813 93.6718 9.44207 95.1354 10.2299C96.5991 11.0178 97.7374 12.1417 98.5506 13.6016C99.3869 15.0615 99.8051 16.7647 99.8051 18.7112ZM93.7066 17.1471C93.7066 16.1275 93.3582 15.3164 92.6612 14.7139C91.9642 14.1114 91.093 13.8102 90.0476 13.8102C89.0486 13.8102 88.2006 14.0998 87.5036 14.6791C86.8299 15.2585 86.4117 16.0811 86.2491 17.1471H93.7066Z"
                            fill="white" />
                        <path
                            d="M114.449 28.7219L110.72 23.3342L107.584 28.7219H101.137L107.549 18.8155L100.962 9.3262H107.653L111.382 14.6791L114.518 9.3262H120.965L114.449 19.0936L121.14 28.7219H114.449Z"
                            fill="white" />
                        <path
                            d="M15.167 9.00708C20.9711 11.0596 27.2305 10.9455 32.9777 8.72202C33.0346 6.38448 32.4087 4.04693 31.3275 1.93745L30.7585 0.797184C30.5878 0.854197 30.3601 0.968232 30.2463 1.08226C25.0112 3.59084 19.0933 3.93292 13.5737 1.93746C9.70432 0.569141 5.49349 0.911216 1.85169 2.73564L0.713624 3.30577C0.770527 3.47681 0.884346 3.70485 0.998152 3.81888C1.68099 5.30122 2.25001 6.8976 2.64833 8.55098C6.63155 7.41072 11.07 7.52473 15.167 9.00708Z"
                            fill="#C69B39" />
                        <path
                            d="M0.9982 26.1682L2.25006 25.484C4.78664 24.2133 7.58497 23.5981 10.3615 23.6792C12.0695 23.7291 13.7692 24.0425 15.3947 24.6288C15.9242 24.817 16.4554 24.9899 16.9879 25.1474L16.9879 31.2245C14.7848 30.8141 12.5544 30.7555 10.3615 31.0383C8.08661 31.3318 5.85196 31.9927 3.72954 33.0097C3.61573 33.1238 3.38812 33.2378 3.21741 33.2948L2.64838 32.1545C1.68103 30.2731 1.11201 28.2206 0.9982 26.1682Z"
                            fill="#C69B39" />
                        <path
                            d="M1.68089 20.9227C6.51766 18.9273 11.9235 18.7562 16.874 20.5236C21.4263 22.12 26.263 22.4051 30.8153 21.3788C30.7584 18.8132 31.0998 16.3047 32.0103 13.7961C26.0354 15.5635 19.6054 15.3925 13.6306 13.283C10.2164 12.0287 6.46075 12.0287 3.04657 13.1689C3.10347 15.6205 2.64826 18.1291 1.79471 20.5806C1.79471 20.5806 1.7378 20.7517 1.68089 20.9227Z"
                            fill="#C69B39" />
                    </g>
                    <defs>
                        <clipPath id="clip0_280_604">
                            <rect width="122" height="34" fill="white" />
                        </clipPath>
                    </defs>
                </svg>
            </a>
            <a @click="closeModal" href="javascript:void(0);" class="js-close-btn">
                <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M26.4305 9.43046L25.0138 8.01379L17.4147 15.6129L9.40092 7.59908L7.98425 9.01575L15.998 17.0295L8.0138 25.0138L9.43046 26.4305L17.4147 18.4462L24.9843 26.0157L26.4009 24.5991L18.8314 17.0295L26.4305 9.43046Z"
                        fill="white" />
                </svg>
            </a>
        </div>
        <form class="modal__body modal-body">
            <h4 class="modal-body__headline">
                Наш специалист ответит
                на все ваши вопросы
            </h4>
            <input class="modal-body__input" type="text" placeholder="Ваше имя">
            <input class="modal-body__input" type="tel" placeholder="Введите ваш номер">
            <button type="submit" class="modal-body__submit">Отправить</button>
            <span class="modal-body__descr">Нажимая на кнопку, вы даете согласие на обработку персональных данных и
                соглашаетесь c политикой конфиденциальности</span>
        </form>
    </div>
    <div class="modal-bg"></div>
</template>

<script>
export default {
    name: 'MainContent',
    methods: {
        openModal() {
            let modal = document.querySelector('.modal');
            let modalBg = document.querySelector('.modal-bg');
            let body = document.querySelector('body');
            modal.classList.add('active');
            modalBg.classList.add('active');
            body.classList.add('fixed');
        },
        closeModal() {
            let modal = document.querySelector('.modal');
            let modalBg = document.querySelector('.modal-bg');
            let body = document.querySelector('body');
            modal.classList.remove('active');
            modalBg.classList.remove('active');
            body.classList.remove('fixed');
        }
    }
}
</script>
<style scoped lang="scss">
.modal {
    display: none;
    position: fixed;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    margin: auto;
    z-index: -1;
    width: 693px;
    max-width: 100%;
    height: max-content;

    &__top {
        padding: 24px 60px;
        background-color: #231F20;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
}

.modal.active {
    display: flex;
    flex-direction: column;
    z-index: 10;

}

.modal-bg {
    display: none;
    position: fixed;
    z-index: -1;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    height: 100vh;
    width: 100vw;
}

.modal-bg.active {
    display: flex;
    z-index: 5;
    background-color: #2A3342;
    opacity: 0.8;
}

.modal-body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 48px 60px;
    row-gap: 36px;
    background-color: #FFFFFF;

    &__headline {
        text-transform: uppercase;
        margin: 0;
        font-size: 24px;
        font-weight: 700;
        line-height: 33.6px;
        letter-spacing: 0.02em;
        color: #231F20;
        margin-bottom: 12px;
    }

    &__input {
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
        letter-spacing: 0.02em;
        padding: 0 0 6px;
        color: #A7A5A6;
        width: 100%;
        border: none;
        border-bottom: 1px solid #231F20;
    }

    &__submit {
        background-color: #231F20;
        cursor: pointer;
        display: flex;
        align-items: center;
        justify-content: center;
        border: none;
        color: #fff;
        width: 100%;
        height: 56px;
        font-size: 16px;
        font-weight: 600;
        line-height: 24px;

        &:hover {
            background-color: #C69B39;
        }
    }

    &__descr {
        color: #444041;
        margin-top: -24px;
        font-size: 12px;
        font-weight: 400;
        line-height: 16.8px;
        letter-spacing: 0.02em;
        text-align: center;
    }
}

.js-close-btn {
    &:hover {
        svg {
            transform: rotate(360deg);

            path {
                fill: #C69B39;
            }
        }
    }
}

.main {
    width: 1200px;
    max-width: 100%;
    margin: 24px auto 0;
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    grid-template-rows: 2;
    grid-column-gap: 0;
    grid-row-gap: 0;

    &__block {
        &:nth-child(1) {
            grid-area: 1 / 1 / 2 / 4;
            display: flex;
            flex-direction: column;
            align-items: flex-start;
            justify-content: center;
            row-gap: 20px;
            padding-right: 24px;
        }

        &:nth-child(2) {
            grid-area: 1 / 4 / 2 / 7;
        }

        &:nth-child(3) {
            grid-area: 2 / 1 / 3 / 7;
        }

        img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    }
}

.headline {
    font-size: 44px;
    font-weight: 700;
    line-height: 61.6px;
    letter-spacing: 0.02em;
    max-width: 560px;
    color: #231F20;
    text-transform: uppercase;
}

.subtitle {
    margin: 0;
    font-size: 20px;
    font-weight: 400;
    line-height: 34px;
    letter-spacing: 0.02em;
    max-width: 560px;
    color: #231F20;
}

.js-form-call {
    margin-top: 12px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    color: #fff;
    background-color: #231F20;
    font-size: 16px;
    font-weight: 700;
    line-height: 24px;
    padding: 16px 76px;

    &:hover,
    :active,
    :focus {
        background-color: #C69B39;
    }
}

.description {
    display: grid;
    margin: 60px auto 0;
    grid-template-columns: 560px 1fr 1fr 205px;
    column-gap: 37px;

    &__text {
        color: #231F20;
        //styleName: Body L;
        font-size: 18px;
        font-weight: 400;
        line-height: 27px;
        letter-spacing: 0.02em;
    }

    &__elem {
        display: flex;
        flex-direction: column;
        align-items: flex-start;

        p {
            margin: 0;

            &:nth-child(1) {
                color: #231F20;
                font-size: 36px;
                font-weight: 600;
                line-height: 50px;
                text-align: left;
                padding-bottom: 10px;
            }

            &:nth-child(2) {
                color: #231F20;
                font-size: 16px;
                font-weight: 400;
                line-height: 24px;
                padding-top: 16px;
                border-top: 2px solid #231F20;
            }
        }
    }
}

@media(max-width:1080px) {
    .main {
        padding: 0 40px;

        &__block {
            img {
                position: relative;
                right: -40px;
            }
        }
    }

    .headline {
        font-size: 28px;
        font-weight: 700;
        line-height: 39px;
        letter-spacing: 0.02em;
        text-align: left;
    }

    .subtitle {
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
        text-align: left;
    }

    .description {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(2, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 0px;
        margin-top: 48px;

        &__text {
            grid-area: 1 / 1 / 2 / 4;
            font-size: 14px;
            font-weight: 400;
            line-height: 19px;
            letter-spacing: 0.02em;
            text-align: left;
        }

        &__elem {
            p {
                &:nth-child(2) {
                    width: 100%;
                }
            }

            &:nth-child(2) {
                grid-area: 2 / 1 / 3 / 2;
                padding-right: 24px;
            }

            &:nth-child(3) {
                grid-area: 2 / 2 / 3 / 3;
                padding-right: 24px;
            }

            &:nth-child(4) {
                grid-area: 2 / 3 / 3 / 4;
            }
        }
    }

    .js-form-call {
        padding: 16px 48px;
    }
}

@media(max-width:610px) {
    .headline {
        font-size: 24px;
        font-weight: 700;
        line-height: 33px;
        letter-spacing: 0.02em;
    }

    .main {
        padding: 0 16px;
        grid-template-columns: 1fr;
        grid-template-rows: unset;
        row-gap: 24px;

        &__block {
            &:nth-child(1) {
                grid-area: unset;
                order: 2;
                overflow: hidden;
                max-width: 100%;
            }

            &:nth-child(2) {
                grid-area: unset;
                order: 1;
            }

            &:nth-child(3) {
                grid-area: unset;
                order: 3;
            }

            grid-area: unset;

            img {
                display: block;
                margin: auto;
                height: 280px;
                width: 360px;
                max-width: 100%;
                right: unset;
            }
        }
    }

    .modal {
        &__top {
            padding: 16px;
        }
    }

    .modal-body {
        padding: 16px;

        &__headline {
            font-size: 18px;
            font-weight: 700;
            line-height: 25px;
            letter-spacing: 0.02em;
        }
    }

    .description {
        margin-top: 0;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: repeat(3, 1fr);
        grid-column-gap: 0px;
        grid-row-gap: 0px;

        &__text {
            grid-area: 1 / 1 / 2 / 3;
            margin-bottom: 20px;
        }

        &__elem {

            &:nth-child(2) {
                grid-area: 2 / 1 / 3 / 2;
                padding-right: 16px;
            }

            &:nth-child(3) {
                grid-area: 2 / 2 / 3 / 3;
                padding-right: 0;
            }

            &:nth-child(4) {
                grid-area: 3 / 1 / 4 / 3;
            }
        }

    }
}
</style>