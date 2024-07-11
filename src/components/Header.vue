<template>
    <header class="header">
        <a href="javascript:void(0);" class="header__logo">
            <svg width="122" height="34" viewBox="0 0 122 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g clip-path="url(#clip0_252_445)">
                    <path
                        d="M68.0653 4.32086V9.08289H58.0987V14.2273H65.5563V18.8503H58.0987V28.7219H52.1396V4.32086H68.0653Z"
                        fill="#231F20" />
                    <path d="M77.1564 3V28.7219H71.1973V3H77.1564Z" fill="#231F20" />
                    <path
                        d="M99.8051 18.7112C99.8051 19.2674 99.7703 19.8467 99.7006 20.4492H86.2143C86.3072 21.6542 86.6905 22.5811 87.3643 23.2299C88.0612 23.8556 88.9092 24.1684 89.9082 24.1684C91.395 24.1684 92.4289 23.5428 93.0097 22.2914H99.3521C99.0268 23.566 98.4344 24.713 97.5748 25.7326C96.7385 26.7522 95.6814 27.5517 94.4036 28.131C93.1258 28.7103 91.6971 29 90.1173 29C88.2122 29 86.5163 28.5945 85.0294 27.7834C83.5425 26.9724 82.3809 25.8137 81.5446 24.3075C80.7082 22.8012 80.29 21.0401 80.29 19.0241C80.29 17.008 80.6966 15.2469 81.5097 13.7406C82.3461 12.2344 83.5077 11.0758 84.9946 10.2647C86.4814 9.45365 88.189 9.04813 90.1173 9.04813C91.9991 9.04813 93.6718 9.44207 95.1354 10.2299C96.5991 11.0178 97.7374 12.1417 98.5506 13.6016C99.3869 15.0615 99.8051 16.7647 99.8051 18.7112ZM93.7066 17.1471C93.7066 16.1275 93.3582 15.3164 92.6612 14.7139C91.9642 14.1114 91.093 13.8102 90.0476 13.8102C89.0486 13.8102 88.2006 14.0998 87.5036 14.6791C86.8299 15.2585 86.4117 16.0811 86.2491 17.1471H93.7066Z"
                        fill="#231F20" />
                    <path
                        d="M114.449 28.7219L110.72 23.3342L107.584 28.7219H101.137L107.549 18.8155L100.962 9.3262H107.653L111.382 14.6791L114.518 9.3262H120.965L114.449 19.0936L121.14 28.7219H114.449Z"
                        fill="#231F20" />
                    <path
                        d="M15.1674 9.00708C20.9715 11.0596 27.2308 10.9455 32.9781 8.72202C33.035 6.38448 32.409 4.04693 31.3279 1.93745L30.7588 0.797184C30.5881 0.854197 30.3605 0.968232 30.2467 1.08226C25.0116 3.59084 19.0937 3.93292 13.5741 1.93746C9.70468 0.569141 5.49385 0.911216 1.85205 2.73564L0.71399 3.30577C0.770893 3.47681 0.884712 3.70485 0.998519 3.81888C1.68136 5.30122 2.25038 6.8976 2.6487 8.55098C6.63192 7.41072 11.0704 7.52473 15.1674 9.00708Z"
                        fill="#C69B39" />
                    <path
                        d="M0.998566 26.1682L2.25042 25.484C4.78701 24.2133 7.58534 23.5981 10.3618 23.6792C12.0698 23.7291 13.7696 24.0425 15.3951 24.6288C15.9245 24.817 16.4557 24.9899 16.9883 25.1474L16.9883 31.2245C14.7851 30.8141 12.5548 30.7555 10.3618 31.0383C8.08698 31.3318 5.85233 31.9927 3.72991 33.0097C3.6161 33.1238 3.38848 33.2378 3.21777 33.2948L2.64874 32.1545C1.68139 30.2731 1.11237 28.2206 0.998566 26.1682Z"
                        fill="#C69B39" />
                    <path
                        d="M1.68126 20.9227C6.51802 18.9273 11.9238 18.7562 16.8744 20.5236C21.4266 22.12 26.2634 22.4051 30.8157 21.3788C30.7588 18.8132 31.1002 16.3047 32.0106 13.7961C26.0358 15.5635 19.6057 15.3925 13.6309 13.283C10.2167 12.0287 6.46112 12.0287 3.04693 13.1689C3.10384 15.6205 2.64863 18.1291 1.79508 20.5806C1.79508 20.5806 1.73816 20.7517 1.68126 20.9227Z"
                        fill="#C69B39" />
                </g>
                <defs>
                    <clipPath id="clip0_252_445">
                        <rect width="122" height="34" fill="white" />
                    </clipPath>
                </defs>
            </svg>
        </a>
        <nav class="header__nav navigation">
            <ul class="navigation-list">
                <li v-for="link in headerLinks" :key="link" class="navigation-list__element">
                    <a href="#" class="navigation-list__link">{{ link }}</a>
                </li>
            </ul>
            <a class="navigation__phone" href="tel:+78128002030">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M20 15.5C18.75 15.5 17.55 15.3 16.43 14.93C16.33 14.9 16.22 14.88 16.12 14.88C15.86 14.88 15.61 14.98 15.41 15.17L13.21 17.37C10.38 15.93 8.06 13.62 6.62 10.78L8.82 8.57C9.1 8.31 9.18 7.92 9.07 7.57C8.7 6.45 8.5 5.25 8.5 4C8.5 3.45 8.05 3 7.5 3H4C3.45 3 3 3.45 3 4C3 13.39 10.61 21 20 21C20.55 21 21 20.55 21 20V16.5C21 15.95 20.55 15.5 20 15.5ZM5.03 5H6.53C6.6 5.88 6.75 6.75 6.98 7.58L5.78 8.79C5.38 7.58 5.12 6.32 5.03 5ZM19 18.97C17.68 18.88 16.4 18.62 15.2 18.21L16.4 17.01C17.25 17.25 18.12 17.4 19 17.46V18.97Z"
                        fill="#231F20" />
                </svg>
                <span>+7 (812) 800-20-30</span>
            </a>
        </nav>
        <div class="mobile-menu-wrapper">
            <a @click="openMenu" href="javascript:void(0);" class="js-menu-btn">
                <svg width="56" height="30" viewBox="0 0 56 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect y="0.5" width="56" height="3" fill="#231F20" />
                    <rect x="14" y="13.5" width="42" height="3" fill="#231F20" />
                    <rect y="26.5" width="56" height="3" fill="#231F20" />
                </svg>
            </a>
            <nav class="header__nav navigation mobile-menu">
                <div class="mobile-menu__top">
                    <a href="javascript:void(0);" class="mobile-menu__logo">
                        <svg width="95" height="32" viewBox="0 0 95 32" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M54.3157 6.71171V10.2986H46.8277V14.1735H52.4306V17.6557H46.8277V25.0913H42.3506V6.71171H54.3157Z"
                                fill="white" />
                            <path d="M61.1459 5.7168V25.0913H56.6688V5.7168H61.1459Z" fill="white" />
                            <path
                                d="M78.162 17.551C78.162 17.9699 78.1358 18.4062 78.0835 18.8601H67.9511C68.0209 19.7677 68.3089 20.4659 68.8151 20.9546C69.3387 21.4259 69.9758 21.6615 70.7264 21.6615C71.8434 21.6615 72.6202 21.1902 73.0565 20.2477H77.8216C77.5773 21.2077 77.1322 22.0717 76.4864 22.8397C75.858 23.6077 75.0638 24.2099 74.1038 24.6462C73.1438 25.0826 72.0704 25.3008 70.8834 25.3008C69.4522 25.3008 68.178 24.9953 67.0609 24.3844C65.9438 23.7735 65.0711 22.9008 64.4427 21.7663C63.8144 20.6317 63.5002 19.3052 63.5002 17.7866C63.5002 16.2681 63.8056 14.9415 64.4165 13.807C65.0449 12.6724 65.9176 11.7997 67.0347 11.1888C68.1518 10.5779 69.4347 10.2724 70.8834 10.2724C72.2973 10.2724 73.554 10.5692 74.6536 11.1626C75.7533 11.7561 76.6085 12.6026 77.2195 13.7023C77.8478 14.8019 78.162 16.0848 78.162 17.551ZM73.5802 16.3728C73.5802 15.6048 73.3184 14.9939 72.7947 14.5401C72.2711 14.0862 71.6165 13.8593 70.8311 13.8593C70.0805 13.8593 69.4434 14.0775 68.9198 14.5139C68.4136 14.9502 68.0994 15.5699 67.9773 16.3728H73.5802Z"
                                fill="white" />
                            <path
                                d="M89.1639 25.0913L86.3624 21.0332L84.0061 25.0913H79.1624L83.9799 17.6295L79.0315 10.4819H84.0584L86.8599 14.5139L89.2162 10.4819H94.0599L89.1639 17.839L94.1908 25.0913H89.1639Z"
                                fill="white" />
                            <path
                                d="M14.5979 9.94644C18.969 11.4921 23.6828 11.4063 28.011 9.73177C28.0539 7.97138 27.5825 6.21099 26.7683 4.62235L26.3398 3.76362C26.2112 3.80656 26.0398 3.89244 25.9541 3.97831C22.0116 5.8675 17.5548 6.12512 13.398 4.62235C10.484 3.59188 7.31285 3.8495 4.57024 5.22346L3.71317 5.65282C3.75602 5.78163 3.84174 5.95337 3.92745 6.03924C4.44169 7.15559 4.87021 8.3578 5.17019 9.60296C8.16992 8.74423 11.5125 8.8301 14.5979 9.94644Z"
                                fill="#C69B39" />
                            <path
                                d="M3.92754 22.87L4.8703 22.3548C6.78059 21.3978 8.888 20.9345 10.979 20.9956C12.2652 21.0332 13.5453 21.2692 14.7694 21.7107C15.1682 21.8525 15.5682 21.9827 15.9693 22.1013L15.9693 26.6779C14.3101 26.3689 12.6305 26.3247 10.979 26.5377C9.26578 26.7587 7.58287 27.2564 5.9845 28.0224C5.89879 28.1082 5.72737 28.1941 5.59881 28.237L5.17028 27.3783C4.44177 25.9614 4.01325 24.4157 3.92754 22.87Z"
                                fill="#C69B39" />
                            <path
                                d="M4.44164 18.9201C8.08418 17.4174 12.1553 17.2885 15.8835 18.6196C19.3118 19.8218 22.9543 20.0365 26.3826 19.2636C26.3397 17.3315 26.5968 15.4423 27.2825 13.5531C22.7829 14.8841 17.9405 14.7553 13.4409 13.1667C10.8697 12.2221 8.04133 12.2221 5.47012 13.0808C5.51298 14.927 5.17016 16.8162 4.52736 18.6625C4.52736 18.6625 4.48449 18.7913 4.44164 18.9201Z"
                                fill="#C69B39" />
                        </svg>

                    </a>
                    <a @click="closeMenu" href="javascript:void(0);" class="js-close-btn">
                        <svg width="34" height="34" viewBox="0 0 34 34" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M26.4305 9.43046L25.0138 8.01379L17.4147 15.6129L9.40092 7.59908L7.98425 9.01575L15.998 17.0295L8.0138 25.0138L9.43046 26.4305L17.4147 18.4462L24.9843 26.0157L26.4009 24.5991L18.8314 17.0295L26.4305 9.43046Z"
                                fill="white" />
                        </svg>
                    </a>
                </div>
                <ul class="navigation-list">
                    <li v-for="link in headerLinks" :key="link" class="navigation-list__element">
                        <a href="#" class="navigation-list__link">{{ link }}</a>
                    </li>
                </ul>
                <a class="navigation__phone" href="tel:+78128002030">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path
                            d="M20 15.5C18.75 15.5 17.55 15.3 16.43 14.93C16.33 14.9 16.22 14.88 16.12 14.88C15.86 14.88 15.61 14.98 15.41 15.17L13.21 17.37C10.38 15.93 8.06 13.62 6.62 10.78L8.82 8.57C9.1 8.31 9.18 7.92 9.07 7.57C8.7 6.45 8.5 5.25 8.5 4C8.5 3.45 8.05 3 7.5 3H4C3.45 3 3 3.45 3 4C3 13.39 10.61 21 20 21C20.55 21 21 20.55 21 20V16.5C21 15.95 20.55 15.5 20 15.5ZM5.03 5H6.53C6.6 5.88 6.75 6.75 6.98 7.58L5.78 8.79C5.38 7.58 5.12 6.32 5.03 5ZM19 18.97C17.68 18.88 16.4 18.62 15.2 18.21L16.4 17.01C17.25 17.25 18.12 17.4 19 17.46V18.97Z"
                            fill="#231F20" />
                    </svg>
                    <span>+7 (812) 800-20-30</span>
                </a>
            </nav>
        </div>
        <div class="mobile-menu-bg"></div>
    </header>
</template>

<script>
export default {
    name: 'HeaderComponent',

    data() {
        return {
            headerLinks: [
                'Наши проекты',
                'О компании',
                'Контакты'
            ],
        };
    },
    methods: {
        openMenu() {
            let mobileMenu = document.querySelector('.mobile-menu');
            let mobileMenuBg = document.querySelector('.mobile-menu-bg');
            let body = document.querySelector('body');
            mobileMenu.classList.add('active');
            mobileMenuBg.classList.add('active');
            body.classList.add('fixed');
        },
        closeMenu() {
            let mobileMenu = document.querySelector('.mobile-menu');
            let mobileMenuBg = document.querySelector('.mobile-menu-bg');
            let body = document.querySelector('body');
            mobileMenu.classList.remove('active');
            mobileMenuBg.classList.remove('active');
            body.classList.remove('fixed');
        }
    }
}
</script>
<style scoped lang="scss">
.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 1200px;
    max-width: 100%;
    margin: 0 auto;
    padding: 26px 0;

    &__logo {
        display: flex;
        align-items: center;
        justify-content: center;
        text-decoration: none;
    }

    &__nav {
        display: flex;
        align-items: center;
        column-gap: 48px;
    }
}

.navigation {
    &__phone {
        display: flex;
        align-items: center;
        column-gap: 12px;
        font-size: 18px;
        font-weight: 600;
        line-height: 25px;
        letter-spacing: 0.02em;
        color: #231F20;
        text-decoration: none;

        &:hover {
            color: #C69B39;
        }
    }
}

.navigation-list {
    padding: 0;
    margin: 0;
    list-style: none;
    display: flex;
    align-items: center;
    column-gap: 36px;
    row-gap: 20px;

    &__link {
        text-decoration: none;
        font-size: 16px;
        font-weight: 500;
        line-height: 24px;
        color: #231F20;

        &:hover {
            color: #C69B39;
        }
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

.mobile-menu,
.mobile-menu-wrapper {
    display: none;
    z-index: -1;
}

.mobile-menu-bg {
    display: none;
    z-index: -1;
}

@media(max-width: 1080px) {
    .header{
        padding: 24px 40px;
    }
    .mobile-menu-wrapper {
        display: flex;
        z-index: 6;
    }

    .mobile-menu {
        padding: 25px 16px;

        &__top {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;
        }
    }
    .mobile-menu-bg.active{
        display: flex;
        z-index: 5;
        position: fixed;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        height: 100vh;
        width: 100vw;
        background-color:#2A3342;
        opacity: 0.8;

    }

    .navigation {
        display: none;
        &__phone{
            color:#fff;
            margin-top: 48px;
            svg{
                path{
                    fill:#fff;
                }
            }
        }
    }

    .navigation.mobile-menu.active {
        display: flex;
        flex-direction: column;
        position: fixed;
        top: 0;
        left: 0;
        width: 360px;
        max-width: 100%;
        height: 100vh;
        align-items: flex-start;
        justify-content: flex-start;
        background-color: #231F20;
        z-index: 10;
    }

    .navigation-list {
        flex-direction: column;
        align-items: flex-start;
        margin-top: 30px;
        &__link {
            color: #fff;
            font-size: 16px;
            font-weight: 500;
            line-height: 24px;
        }
    }

}
@media(max-width:610px){
    .header{
        padding: 24px 16px;
    }
}
</style>