<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.net/npm/swiper/swiper-bundle.min.css">
    <link rel="stylesheet" href="style.css">
    
    
</head>
<body>
    <header>
        <div class="menu container">
            <img class = "logo-1" src= "img/logo.svg" alt="">
            <input type="checkbox" id="menu" />
            <label for="menu">
                <img src="img/menu.png" class="menu-icono" alt="">
            </label>
            <nav class="navbar">
                <div class="menu-1">
                    <ul>
                        <li><a href="#">Inicio</a></li>
                        <li><a href="#">Servicios</a></li>
                        <li><a href="#">Productos</a></li>
                    </ul>
                </div>
                <img class="logo-2" src="img/logo.svg" alt="">
                <div class="menu-2">
                    <ul>
                        <li><a href="#">Horario</a></li>
                    </ul>
                    <div class="socials">
                        <a href="#">
                            <div class="social">
                                <img src="img/s1.svg" alt="">
                            </div>
                        </a>
                        <a href="#">
                            <div class="social">
                                <img src="img/s2.svg" alt="">
                            </div>
                        </a>
                        <a href="#">
                            <div class="social">
                                <img src="img/s3.svg" alt="">
                            </div>
                        </a>
                    </div>
                </div>
            </nav>
        </div>

        <div class="header-content container">

            <div class="swiper mySwiper-1">
                <div class="swiper-wrapper">

                    <div class="swiper-slide">
                        <div class="slider">
                            <div class="slider-txt">
                                <h1>Hamburguesa</h1>
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    Blanditiis aperiam eum 
                                    perspiciatis quasi eligendi fugiat nobis placeat. 
                                    Rerum animi voluptatibus nesciunt quisquam veritatis?
                                </p>
                                <div class="botones">
                                    <a href="#" class="btn-1">Comprar</a>
                                    <a href="#" class="btn-2">Menu</a>
                                </div>
                            </div>
                            <div class="slider-img">
                                <img src="img/slider1.png" alt="">
                            </div>
                        </div>
                    </div>

                    <div class="swiper-slide">
                        <div class="slider">
                            <div class="slider-txt">
                                <h1>Torta</h1>
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    Blanditiis aperiam eum 
                                    perspiciatis quasi eligendi fugiat nobis placeat. 
                                    Rerum animi voluptatibus nesciunt quisquam veritatis?
                                </p>
                                <div class="botones">
                                    <a href="#" class="btn-1">Comprar</a>
                                    <a href="#" class="btn-2">Menu</a>
                                </div>
                            </div>
                            <div class="slider-img">
                                <img src="img/slider2.png" alt="">
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="slider">
                            <div class="slider-txt">
                                <h1>Hamburguesa</h1>
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                    Blanditiis aperiam eum 
                                    perspiciatis quasi eligendi fugiat nobis placeat. 
                                    Rerum animi voluptatibus nesciunt quisquam veritatis?
                                </p>
                                <div class="botones">
                                    <a href="#" class="btn-1">Comprar</a>
                                    <a href="#" class="btn-2">Menu</a>
                                </div>
                            </div>
                            <div class="slider-img">
                                <img src="img/slider3.png" alt="">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="swiper-button-next"></div>
                <div class="swiper-button-prev"></div>
                <div class="swiper-pagination"></div>
            </div>
        </div>
    </header>

    <main class="products">
        <div class="tabs container">

            <input type="radio" name="tabs" id="tab1" checked = "checked" class="tabInput" value="1">
            <label for="tab1">Hamburguesa</label>
            <div class="tab">
                <div class="swiper mySwiper-2" id="swiper1">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food1.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food2.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food3.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-buttom-next"></div>
                    <div class="swiper-buttom-prev"></div>
                </div>
            </div>

            <input type="radio" name="tabs" id="tab2" checked = "checked" class="tabInput" value="2">
            <label for="tab2">Burritos</label>
            <div class="tab">
                <div class="swiper mySwiper-2" id="swiper2">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food4.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food5.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food6.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-buttom-next"></div>
                    <div class="swiper-buttom-prev"></div>
                </div>
            </div>

            <input type="radio" name="tabs" id="tab2" checked = "checked" class="tabInput" value="2">
            <label for="tab2">Variedad</label>
            <div class="tab">
                <div class="swiper mySwiper-2" id="swiper3">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food7.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food8.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="product">
                                <div class="product-img">
                                    <h4>Nuevo</h4>
                                    <img src="img/food9.png" alt="">
                                </div>
                                <div class="product-txt">
                                    <h4>Producto</h4>
                                    <p>calidad premium</p>
                                    <span class="price">$80.00</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-buttom-next"></div>
                    <div class="swiper-buttom-prev"></div>
                </div>
            </div>


        </div>

    </main>


    <section class="info container">

        <div class="info-img">
            <img src="img/info.png" alt="">
        </div>

        <div class="info-txt">
            <h2>Informacion</h2>
            <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
                Id quo ipsum aliquam corrupti velit excepturi 
                laboriosam adipisci quae quam voluptates tempora harum, 
                explicabo ad, facere aliquid dolore praesentium iure doloremque?
            </p>
            <a href="#" class="btn-2">Mas Informacion</a>

        </div>

    </section>

    <section class="horario">
        <div class="horario-info container">
            <h2>Horario</h2>
            <div class="horario-txt">
                <div class="txt">
                    <h4>Direccion</h4>
                    <p>
                        quae quam voluptates tempor
                    </p>

                    <p>
                        ipsum dolor sit, amet consectetur adipisicing
                    </p>
                </div>
                <div class="txt">
                    <h4>Horario</h4>
                    <p>
                        Lunes a Viernes : 9 am - 8 pm
                    </p>
                    <p>
                        Sabado y Domingo : 11 am - 7 pm
                    </p>
                </div>
                <div class="txt">
                    <h4>Telefono</h4>
                    <p>
                        504242341242654
                    </p>
                    <p>
                        42534564754774
                    </p>
                </div>
                <div class="txt">
                    <h4>Redes Sociales</h4>
                    <div class="socials">
                        <a href="#">
                            <div class="social">
                                <img src="img/s1.svg" alt="">
                            </div>
                        </a>
                        <a href="#">
                            <div class="social">
                                <img src="img/s2.svg" alt="">
                            </div>
                        </a>
                        <a href="#">
                            <div class="social">
                                <img src="img/s3.svg" alt="">
                            </div>
                        </a>
                    </div>
                    
                </div>
            </div>
        </div>
    </section>

    <section>
        <iframe class = "map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d255168.19789702145!2d-79.9801008!3d-2.15250125!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x902d13cbe855805f%3A0x8015a492f4fca473!2sGuayaquil!5e0!3m2!1ses-419!2sec!4v1718058097575!5m2!1ses-419!2sec" width="100%" height="500" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </section>

    <footer class="footer container">
        <img  class="logo-2"   src="img/logo.svg" alt="">
        <div class="links">
            <h4>Lorem </h4>
            <ul>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem </a></li>
            </ul>
        </div>
        <div class="links">
            <h4>Lorem </h4>
            <ul>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem </a></li>
            </ul>
        </div>
        <div class="links">
            <h4>Lorem </h4>
            <ul>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem</a></li>
                <li><a href="#">Lorem </a></li>
            </ul>
        </div>
        <div class="links">
            <h4>Lorem </h4>
            <div class="socials">
                <a href="#">
                    <div class="social">
                        <img src="img/s1.svg" alt="">
                    </div>
                </a>
                <a href="#">
                    <div class="social">
                        <img src="img/s2.svg" alt="">
                    </div>
                </a>
                <a href="#">
                    <div class="social">
                        <img src="img/s3.svg" alt="">
                    </div>
                </a>
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdeliver.net/npm/swiper-bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
