<template>
  <div id="app">
        <!-- navbar -->
        <div class="navbar-style">
            <nav class="navbar navbar-expand-lg navbar-light container">
                <div class="container-fluid">
                    <div>
                        <a class="navbar-brand" href="#">
                            <img src="./img/banana.png" alt="" width="30" height="24"
                                class="d-inline-block align-text-top">
                            笨NaNa
                        </a>
                    </div>
                </div>

                <div class="container-fluid">
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">首頁</a>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                                    data-bs-toggle="dropdown" aria-expanded="false">
                                    文章
                                </a>
                                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                    <li><a class="dropdown-item" href="#">所有文章</a></li>
                                    <li><a class="dropdown-item" href="#">初學者專區</a></li>
                                    <li><a class="dropdown-item" href="#">材料包教學</a></li>
                                </ul>
                            </li>

                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                                    data-bs-toggle="dropdown" aria-expanded="false">
                                    產品
                                </a>
                                <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                                    <li><a class="dropdown-item" href="#">所有產品</a></li>
                                    <li><a class="dropdown-item" href="#">材料包</a></li>
                                    <li><a class="dropdown-item" href="#">編織產品</a></li>
                                    <li><a class="dropdown-item" href="#">寵物用品</a></li>
                                    <li><a class="dropdown-item" href="#">毛線材料</a></li>
                                </ul>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#">收藏</a>
                            </li>

                            <li class="nav-item">
                                <a class="nav-link" href="#">購物車</a>
                            </li>

                        </ul>

                    </div>
                    <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-outline-success text-nowrap" type="submit">找尋</button>
                    </form>
                </div>
            </nav>
        </div>

        <!-- banner -->
        <section class="section1">
            <div class="container">
                <div class="row">
                    <div class="col-6">
                        <h1>歡迎來到<br>萬物皆可織の織物世界</h1>
                        <form class="d-flex">
                            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                            <!-- <button class="btn btn-outline-success text-nowrap" type="submit">找尋</button> -->
                        </form>
                    </div>
                    <div class="col-6">img</div>
                </div>
            </div>

        </section>

        <!--品牌理念 -->
        <section class="section2">
            <div class="container d-flex flex-column align-items-center ">
                <img src="./img/banana.png" alt="" width="70" class="my-2">

                <h3 class="my-2 text-title">笨NaNa 品牌理念</h3>
                <p class="text-container my-4">
                    尊重和保留傳統的編織技藝，同時結合現代設計理念，通過手工編織，創造出獨特和高質量的產品。尊重和保留傳統的編織技藝，同時結合現代設計理念，通過手工編織，創造出獨特和高質量的產品。尊重和保留傳統的編織技藝，同時結合現代設計理念，通過手工編織，創造出獨特和高質量的產品。
                </p>
            </div>
        </section>

        <!--精選文章 -->
        <section class="section3">
            <div class="container d-flex flex-column align-items-center ">
                <img src="./img/banana.png" alt="" width="70" class="my-2">

                <h3 class="my-2 text-title">精選文章</h3>
                <!-- Swiper -->
                <div class="swiper mySwiper my-4">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide d-flex flex-column" style="flex-direction: column;">
                            <img src="./img/pexels-surene-palvie-2070676.jpg" alt="">
                            <div class="py-4">
                                <h4 style="text-align: left;" class="title-setting">
                                    想學編織卻不知如何準備嗎？新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人新手懶人</h4>
                                <p style="text-align: left;">2023.03.03</p>
                            </div>
                        </div>

                        <div class="swiper-slide d-flex flex-column" style="flex-direction: column;">
                            <img src="./img/pexels-surene-palvie-2070676.jpg" alt="">
                            <div class="py-4">
                                <h4 style="text-align: left;" class="title-setting">想學編織卻不知如何準備嗎？新手懶人</h4>
                                <p style="text-align: left;">2023.03.03</p>
                            </div>
                        </div>

                        <div class="swiper-slide d-flex flex-column" style="flex-direction: column;">
                            <img src="./img/pexels-surene-palvie-2070676.jpg" alt="">
                            <div class="py-4">
                                <h4 style="text-align: left;" class="title-setting">想學編織卻不知如何準備嗎？新手懶人</h4>
                                <p style="text-align: left;">2023.03.03</p>
                            </div>
                        </div>

                        <div class="swiper-slide d-flex flex-column" style="flex-direction: column;">
                            <img src="./img/pexels-surene-palvie-2070676.jpg" alt="">
                            <div class="py-4">
                                <h4 style="text-align: left;" class="title-setting">想學編織卻不知如何準備嗎？新手懶人</h4>
                                <p style="text-align: left;">2023.03.03</p>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-button-next"></div>
                    <div class="swiper-button-prev"></div>
                    <div class="swiper-pagination"></div>

                </div>
                <a class="btn-style1 btn-color1 my-2 d-inline-block">了解更多</a>
            </div>

        </section>

        <!--熱門商品 -->
        <section class="section4">
            <div class="container d-flex flex-column align-items-center">
                <img src="./img/banana.png" alt="" width="70" class="my-2">

                <h3 class="my-2 text-title">熱門商品</h3>

                <!-- Swiper -->
                <div class="swiper mySwiper my-4">
                    <div class="swiper-wrapper"  >

                        <div class="swiper-slide d-flex flex-column" style="flex-direction: column;" v-for="item in products" :key="item.id">
                            <img src="./img/pexels-surene-palvie-2070676.jpg" alt="">
                            <a href="" class="icon-cycle"><img src="./img/like.png" alt="like" class="icon-style"></a>
                            <a href="" class="icon-cycle2"><img src="./img/shopping-cart.png" alt="cart"
                                    class="icon-style2 "></a>
                            <div class="py-4">
                                <h4 style="text-align: left;" class="title-setting">
                                    {{item.title}}</h4>
                                <p style="text-align: left;">NT${{item.price}}</p>
                            </div>

                        </div>

                    </div>
                    <div class="swiper-button-next"></div>
                    <div class="swiper-button-prev"></div>
                    <div class="swiper-pagination"></div>
                </div>
                <a class="btn-style1 btn-color2 my-2">了解更多</a>
            </div>

        </section>

        <!-- footer -->
        <footer>
            <div class="py-5 container">
                <div class="row">
                    <div class="col-2">
                        <h5>Section</h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Home</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Features</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Pricing</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">FAQs</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">About</a></li>
                        </ul>
                    </div>

                    <div class="col-2">
                        <h5>Section</h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Home</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Features</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Pricing</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">FAQs</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">About</a></li>
                        </ul>
                    </div>

                    <div class="col-2">
                        <h5>Section</h5>
                        <ul class="nav flex-column">
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Home</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Features</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">Pricing</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">FAQs</a></li>
                            <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted">About</a></li>
                        </ul>
                    </div>

                    <div class="col-4 offset-1">
                        <form>
                            <h5>Subscribe to our newsletter</h5>
                            <p>Monthly digest of whats new and exciting from us.</p>
                            <div class="d-flex w-100 gap-2">
                                <label for="newsletter1" class="visually-hidden">Email address</label>
                                <input id="newsletter1" type="text" class="form-control" placeholder="Email address">
                                <button class="btn btn-primary" type="button">Subscribe</button>
                            </div>
                        </form>
                    </div>
                </div>

                <div class="d-flex justify-content-between py-4 my-4 border-top">
                    <p>© 2022 Company, Inc. All rights reserved.</p>
                    <ul class="list-unstyled d-flex">
                        <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24">
                                    <use xlink:href="#twitter"></use>
                                </svg></a></li>
                        <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24">
                                    <use xlink:href="#instagram"></use>
                                </svg></a></li>
                        <li class="ms-3"><a class="link-dark" href="#"><svg class="bi" width="24" height="24">
                                    <use xlink:href="#facebook"></use>
                                </svg></a></li>
                    </ul>
                </div>
            </div>
        </footer>
    </div>
</template>

<style scoped>

</style>
