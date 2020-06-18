<template>
    <div id="app">
        <div v-if="showModal" class="absolute pin p-8 w-full h-full" style="background-color: hsla(0, 0%, 0%, .5)">
            <div @click.stop class="max-w-sm w-full mx-auto bg-white rounded p-6 mt-8 z-10 shadow-lg relative">
                <button @click="showModal = false" class="absolute right-0 top-0 pt-1 p-2">
                    <i class="fa fa-window-close"></i>
                </button>
                <h1 class="font-normal text-xl text-center mb-6">
                    Select Language
                </h1>
                <div class="mb-6">
                    <div class="container mx-auto">
                        <div @click="selectedLanguage(0)"
                             class="cursor-pointer border m-2 rounded-lg bg-white mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
                            <div class="px-6 py-3 flex flex-row">
                                <div class="block rounded-full w-auto">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 60 30" width="60" height="30">
                                        <clipPath id="s">
                                            <path d="M0,0 v30 h60 v-30 z"/>
                                        </clipPath>
                                        <clipPath id="t">
                                            <path d="M30,15 h30 v15 z v15 h-30 z h-30 v-15 z v-15 h30 z"/>
                                        </clipPath>
                                        <g clip-path="url(#s)">
                                            <path d="M0,0 v30 h60 v-30 z" fill="#012169"/>
                                            <path d="M0,0 L60,30 M60,0 L0,30" stroke="#fff" stroke-width="6"/>
                                            <path d="M0,0 L60,30 M60,0 L0,30" clip-path="url(#t)" stroke="#C8102E"
                                                  stroke-width="4"/>
                                            <path d="M30,0 v30 M0,15 h60" stroke="#fff" stroke-width="10"/>
                                            <path d="M30,0 v30 M0,15 h60" stroke="#C8102E" stroke-width="6"/>
                                        </g>
                                    </svg>
                                </div>
                                <div class="text-left ml-3">
                                    <p class="text-xl leading-tight mt-1">English</p>
                                </div>
                            </div>
                        </div>
                        <div @click="selectedLanguage(1)"
                             class="cursor-pointer border m-2 rounded-lg bg-white mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
                            <div class="px-6 py-3 flex flex-row">
                                <div class="block rounded-full w-auto">
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 9 6" width="60" height="30">
                                        <rect fill="#fff" width="9" height="3"/>
                                        <rect fill="#d52b1e" y="3" width="9" height="3"/>
                                        <rect fill="#0039a6" y="2" width="9" height="2"/>
                                    </svg>
                                </div>
                                <div class="text-left ml-3">
                                    <p class="text-xl leading-tight mt-1">Русский</p>
                                </div>
                            </div>
                        </div>
                        <div @click="selectedLanguage(2)"
                             class="cursor-pointer border m-2 rounded-lg bg-white mx-auto max-w-sm shadow-lg rounded-lg overflow-hidden">
                            <div class="px-6 py-3 flex flex-row">
                                <div class="block rounded-full w-auto">
                                    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                         width="60" height="30" viewBox="0 0 1400 700">
                                        <rect width="1400" fill="#060" height="700"/>
                                        <rect width="1400" fill="#fff" height="500"/>
                                        <rect width="1400" fill="#c00" height="200"/>
                                        <g fill="#f8c300">
                                            <path d="M 672.0,340.7 a 12.5,12.5 0,0,1 23.3,5.9 v 50 h 9.4 v -50 a 12.5,12.5 0,0,1 23.3,-5.9 a 29.5,29.5 0,1,0 -56,0"/>
                                            <path d="M 678.7,327.65 a 20,20 0,0,1 21.3,9.55 a 20,20 0,0,1 21.3,-9.55 a 21.5,21.5 0,0,0 -42.6,0"
                                                  fill="#fff"/>
                                            <path id="w"
                                                  d="M 695.3,376.627 a 38,38 0 0 1 -63.845,24.316 a 39.5,39.5 0 0 1 -59.734,17.467 c 3.6496,36.426 58.252,28.989 62.32,-6.4288 17.154,30.115 54.873,21.49 65.91,-15.4 z"/>
                                            <use xlink:href="#w"
                                                 transform="translate(700,0) scale(-1,1) translate(-700,0)"/>
                                            <path id="r"
                                                  d="M 658.84,441.31 c -7.6181,16.446 -22.845,19.271 -36.164,5.9953 0,0 5.3539,-3.7831 11.086,-4.826 -1.0748,-4.5744 1.1291,-10.902 4.2354,-14.324 3.2575,2.2264 7.8036,6.6886 8.9598,11.874 8.0291,-1.0394 11.883,1.2815 11.883,1.2815 z"/>
                                            <use xlink:href="#r" transform="rotate(9.37, 700,804)"/>
                                            <use xlink:href="#r" transform="rotate(18.74, 700,804)"/>
                                            <path d="M 603,478 a 340,340 0 0 1 194,0" fill="none" stroke-width="16"
                                                  stroke="#f8c300"/>
                                            <g transform="translate(700,380)">
                                                <g transform="translate(0,-140)">
                                                    <polygon id="s"
                                                             points="0,-513674 301930,415571 -488533,-158734 488533,-158734 -301930,415571"
                                                             transform="scale(0.000048669)"/>
                                                </g>
                                                <g id="h">
                                                    <use xlink:href="#s"
                                                         transform="rotate(-30) translate(0,-140) rotate(30)"/>
                                                    <use xlink:href="#s"
                                                         transform="rotate(-60) translate(0,-140) rotate(60)"/>
                                                    <use xlink:href="#s"
                                                         transform="rotate(-90) translate(0,-140) rotate(90)"/>
                                                </g>
                                                <use xlink:href="#h" transform="scale(-1,1)"/>
                                            </g>
                                        </g>
                                    </svg>
                                </div>
                                <div class="text-left ml-3">
                                    <p class="text-xl leading-tight mt-1">Тоҷикӣ</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="text-center">
                    <p class="text-gray-400">&copy; ehson.tj</p>
                </div>
            </div>
        </div>

        <nav class="flex items-center justify-center flex-wrap bg-white shadow p-3 sm:w-full">
            <div class="flex w-90 justify-between">
                <div class="flex items-center flex-shrink-0 text-white mr-6">
                    <a href="/"><img class="brand-logo" src="@/assets/img/ehson.png" alt="logo"></a>
                </div>
                <div class="block lg:hidden">
                    <button class="flex items-center px-3 py-2 border rounded text-gray-500 border-teal-400 hover:text-black hover:border-white">
                        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>
                            Menu</title>
                            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/>
                        </svg>
                    </button>
                </div>
                <div class="w-full lg:block hidden flex-grow lg:flex lg:items-center lg:w-auto">
                    <div class="text-sm lg:flex-grow">
                        <a href="/about"
                           class="block mt-4 lg:inline-block lg:mt-0 text-gray-700 hover:text-black mr-4">
                            {{ langPack[currentLang].about }}
                        </a>
                    </div>
                    <div>
                        <a href="#"
                           class="inline-block text-sm px-4 py-2 leading-none border rounded text-teal-700 bg-teal-100 border-white hover:border-transparent hover:text-teal-500 hover:bg-teal-100 mt-4 lg:mt-0">{{
                            langPack[currentLang].donate }}</a>
                    </div>
                </div>
            </div>
        </nav>

        <router-view/>

        <div class="footer flex justify-center pt-5 pb-5">
            <div class="w-90">
                <div class="row flex lg:flex-row flex-wrap">
                    <div class="flex flex-wrap lg:w-1/2 w-full">
                        <a href="https://megafon.tj/">
                            <img class="brand-logo footer" src="@/assets/img/ehson.png" alt="">
                        </a>
                        <div class="text-sm w-90 pt-3 pb-2">
                            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur, corporis deserunt, eaque eveniet exercitationem illum inventore ipsa magnam minus necessitatibus quam, quis unde. Dolore esse ipsam libero placeat, sit sunt.
                        </div>
                        <div class="flex flex-row">
                            <a href="#" class="flex">
                                <img class="w-8 p-1" src="@/assets/img/telegram.svg" alt="">
                            </a>
                            <a href="#" class="flex">
                                <img class="w-8 p-1" src="@/assets/img/facebook.svg" alt="">
                            </a>
                            <a href="#" class="flex">
                                <img class="w-8 p-1" src="@/assets/img/vkontakte.svg" alt="">
                            </a>
                            <a href="#" class="flex">
                                <img class="w-8 p-1" src="@/assets/img/viber.svg" alt="">
                            </a>
                            <a href="#" class="flex">
                                <img class="w-8 p-1" src="@/assets/img/instagram.svg" alt="">
                            </a>
                        </div>
                    </div>
                    <div class="flex flex-wrap lg:w-1/2 w-full flex flex-row">
                        <div class="lg:w-1/3 xl:w-1/3 w-1/2 p-3">
                            <h2 class="font-bold text-xl text-gray-700">Lorem</h2>
                            <ul class="">
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                            </ul>
                        </div>

                        <div class="lg:w-1/3 xl:w-1/3 w-1/2 p-3">
                            <h2 class="font-bold text-xl text-gray-700">Lorem</h2>
                            <ul class="">
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                                <li class=""><a href="" class="text-gray-600">Lorem</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>


</template>

<script>

    export default {
        name: 'App',
        components: {},
        data() {
            return {
                showModal: true,
                currentLang: 0,
                langPack: [
                    {
                        about: 'About',
                        donate: 'To Donate',
                    },
                    {
                        about: 'О нас',
                        donate: 'Пожертвовать',
                    },
                    {
                        about: 'Да бораи мо',
                        donate: 'Ба хайрия',
                    },
                ]
            }
        },
        created() {
            var cl = localStorage.getItem('currentLang')
            document.title = 'Home page'
            if (cl != null && cl != undefined){
                this.showModal = false
            }
        },
        methods: {
            selectedLanguage(id) {
                this.showModal = false
                this.currentLang = id
                localStorage.setItem('currentLang', this.currentLang);
            }
        }
    }
</script>

<style>
    .brand-logo {
        width: 120px;
    }

    .brand-logo.footer {
        width: 220px;
    }

    .w-90 {
        width: 90%;
    }
</style>
