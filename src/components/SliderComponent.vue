<template>
    <section class="slider-block">
        <h2 class="headline headline_secondary">
            <div class="text-line"></div>
            <span>Юмористические вставки или слова</span>
        </h2>
        <carousel :breakpoints="breakpoints" :wrapAround="true" :items-to-show="3">
            <slide class="slider-element" v-for="slider in sliderData" :key="slider">
                <div class="slider-element__img">
                    <img :src="require(`${slider.image}`)" alt="image">
                </div>
                <a href="javascript:void(0);" class="slider-element__tag">
                    #tag
                </a>
                <a class="slider-element__link" href="javascript:void(0);">
                    <h3 class="slider-element__headline">{{ slider.title }}</h3>
                    <p class="slider-element__descr">{{ slider.description }}</p>
                </a>
            </slide>

            <template #addons>
                <pagination />
            </template>
        </carousel>
    </section>
</template>

<script>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Pagination } from 'vue3-carousel'

export default {
    name: 'SliderComponent',
    components: {
        Carousel,
        Slide,
        Pagination,
    },

    data() {
        return {
            sliderData: [
                { title: 'оценка дизайна', description: 'За прошедшие годы текст Lorem Ipsum получил много версий', image: './img/slide-1.png' },
                { title: 'Lorem Ipsum в качестве текста по умолчанию', description: 'Многие программы электронной вёрстки и редакторы HTML используют Lorem Ipsum в качестве текста по умолчанию', image: './img/slide-2.png' },
                { title: 'Почему он используется?', description: 'Это делает предлагаемый здесь генератор единственным настоящим Lorem Ipsum генератором.', image: './img/slide-3.png' }
            ],
            settings: {
                itemsToShow: 1,
                snapAlign: 'center',
            },

            breakpoints: {
                280: {
                    itemsToShow: 4,
                    itemsToScroll: 0,
                    wrapAround: false,
                    mouseDrag: false,
                    touchDrag: false,
                    snapAlign: 'center',
                },
                1081: {
                    itemsToShow: 3,
                    itemsToScroll: 1,
                    wrapAround: true,
                    mouseDrag: true,
                    touchDrag: true,
                    snapAlign: 'start',
                },
            },
        };
    },
}
</script>
<style lang="scss">
.headline {
    &_secondary {
        color: #231F20;
        font-size: 48px;
        font-weight: 600;
        line-height: 67px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        column-gap: 40px;
        margin-bottom: 60px;

        .text-line {
            width: 80px;
            height: 3px;
            background-color: #231F20;
        }
    }
}

.slider-block {
    display: flex;
    flex-direction: column;
    width: 1200px;
    max-width: 100%;
    overflow: hidden;
    margin: 120px auto 0;
}

.slider-element {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    width: 384px;
    position: relative;
    overflow: hidden;

    &:hover {
        img {
            transform: scale(1.2);
        }
    }

    &__img {
        overflow: hidden;
        height: 248px;
        width: 384px;
    }

    &__tag {
        position: absolute;
        top: 12px;
        left: 12px;
        background-color: #231F20;
        border-bottom-right-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
        color: #fff;
        padding: 8px 16px;

        &:hover {
            color: #231F20;
            background-color: #EEEDEE;
        }
    }

    &__link {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: flex-start;
        text-decoration: none;
        margin-top: 20px;
        row-gap: 12px;

        &:hover {
            h3 {
                color: #C69B39;
            }
        }
    }

    &__headline {
        text-transform: uppercase;
        font-size: 18px;
        font-weight: 700;
        line-height: 25.2px;
        letter-spacing: 0.02em;
        text-align: left;
        color: #231F20;
    }

    &__descr {
        margin: 0;
        color: #231F20;
        font-size: 16px;
        font-weight: 400;
        line-height: 24px;
        text-align: left;
    }
}

.carousel__pagination-button::after {
    width: 48px;
    background-color: #232323;
    height: 3px;
}

.carousel__pagination-button--active::after {
    width: 48px;
    background-color: #C69B39;
    height: 3px;
}

@media(max-width:1080px) {
    .slider-block {
        margin-top: 80px;
        padding: 0 40px;
    }

    .headline_secondary {
        font-size: 32px;
        font-weight: 600;
        line-height: 45px;
        margin-bottom: 48px;
    }

    .carousel__track {
        flex-direction: column;
        row-gap: 48px;
        transform: none !important;

        .carousel__slide {
            width: 100% !important;
        }
    }

    .carousel__pagination {
        display: none;
    }

    .slider-element {
        background-color: #2A334280;

        &__img {
            width: 690px;
            height: 320px;
            margin: 0 auto;
        }

        &__link {
            background-color: #fff;
            width: 100%;
            margin-top: 0;
            padding-top: 20px;
        }

        &__headline {
            font-size: 18px;
            font-weight: 700;
            line-height: 25px;
            letter-spacing: 0.02em;
        }

        &__descr {
            font-size: 16px;
            font-weight: 400;
            line-height: 24px;
        }
    }
}

@media(max-width:610px) {
    .slider-block {
        margin-top: 60px;
        padding: 0 16px;
    }

    .headline {
        &_secondary {
            display: grid;
            grid-template-columns: 30px 1fr;
            column-gap: 20px;
            font-size: 24px;
            font-weight: 600;
            line-height: 33px;
            letter-spacing: 0.01em;
            .text-line{
                width: 30px;
            }
        }
    }
}
</style>