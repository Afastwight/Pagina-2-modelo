<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food</title>
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

                @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap");

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
}

body{
    background-color: #080202;
    font-family: 'Poppins', sans-serif;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

.swiper-buttom-prev::after{
    font-size: 25px;
    
}
.swiper-buttom-next::after{
    font-size: 25px;
}
.swiper-buttom-next{
    color: #DB2418;
}
.swiper-buttom-prev{
    color: #DB2418;
}

.swiper-pagination-bullet{
    background-color: #d3d2d2;
    opacity: 1;
}
.swiper-pagination-bullet-active{
    background-color: #DB2418;
}


.menu {
    position: absolute;
    top: 20px;
    left: 0;
    right: 0;
    display: flex;
    justify-content: center;
    z-index: 1000;
}

.navbar{
    display: flex;
}
.menu-1{
    margin-right: 180px;
}
.menu-2{
    margin-left: 180px;
    display: flex;
    align-items: center;
}
.log-1{
width: 0;
}

.log-2{
    width: 150px;
}

.socials{
    display: flex;
}

.social{
    margin: 0 10px;
    height: 40px;
    width: 40px;
    border: 1px solid #DB2418;
    border-radius: 50%;
}

.social:hover{
    background-color: #DB2418;
}

.social img{
    margin: 8px 0 0 10px;
}

.menu .navbar ul li{
    position: relative;
    float: left;
}

.menu .navbar ul li a{
    font-size: 18px;
    padding: 20px;
    color: #ffffff;
    display: block;
}

.menu .navbar ul li a:hover{
    color: #DB2418;
}

#menu {
    display: none;
}

.menu-icono{
    width: 25px;
}
.menu label{
    cursor: pointer;
    display: none;
}



.header{
    margin-top: 200px;
    padding-bottom: 50px;
}
.slider{
    display: flex;
    align-items: center;
}
.slider-txt{
    margin-left: 85px;
    width: 50%;
}
.slider-txt h1{
    font-size: 70px;
    color: #ffffff;
    text-transform: uppercase;
    font-weight: 800;
}
.slider-txt p{
    font-size: 18px;
    color: #a7a7a7;
}



.botones{
    margin-top: 50px;

}
.btn-1{
    display: inline-block;
    padding: 15px 35px;
    border: 2px solid #DB2418;
    color: #ffffff;
    font-weight: 800;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-right: 20px;
    border-radius: 50px;
}
.btn-2{
    display: inline-block;
    padding: 15px 35px;
    border: 2px solid #DB2418;
    color: #ffffff;
    font-weight: 800;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-right: 20px;
    border-radius: 50px;
}

.btn-1:hover{
    background-color: #DB2418;
}


.slider-img{
    width: 50%;
}
.slider-img img{
    margin-right: 225px;
    width: 550px;
}



.prducts{
    background-color: #0d0d0d;
}
.tabs{
    display: flex;
    flex-wrap: wrap;
    padding: 100px 0px;
}
.tabs label{
    width: 15%;
    order: 1;
    display: block;
    padding: 20px 0 ;
    text-align: center;
    cursor: pointer;
    color: #a7a7a7;
    font-weight: 700;
    font-size: 18px;
    text-transform: uppercase;
    transition: background ease 0.2s;
}
.tabs .tab{
    order: 99;
    flex-grow: 1;
    width: 100%;
    display: none;
    padding-top: 25px;
}

.tabs input[type="radio"]{
    display: none;
}
.tabs input[type="radio"]:checked + label{
    border-bottom: 2px solid #DB2418;
    color: #ffffff;
}
.tabs input[type="radio"]:checked + label + .tab{
    display: block;
}

.prducts{
    display: flex;
    align-items: center;
    padding: 25px;
    margin: 0 10px;

}
.product-img{
    width: 50%;
    text-align: left;
}
.product-img h4{
    display: inline-block;
    padding: 5px 7px;
    line-height: 15px;
    color: #ffffff;
    font-size: 14px;
    text-transform: uppercase;
    font-weight: 800;
    border: 2px solid #555555;
    border-radius: 10px;
    margin-bottom: 50px;
}

.prducts-img img{
    width: 150px;
    height: 120px;
}
.prducts-txt{
    width: 50px;
    margin-left: 10px;
    text-align: left;
}
.product-txt h4{
    color: #ffffff;
    font-size: 18px;
    text-transform: uppercase;
    font-weight: 800;
    margin-bottom: 5px;
}
.product-txt p{
    color: #a7a7a7;
    font-size: 16px;
    margin-bottom: 15px;
}
.prducts-txt span{
    color: #ffffff;
    font-size: 18px;
    font-weight: 800;

}


.info{
    padding: 100px 0px;
    display: flex;
    align-items: center;
}
.info-img{
    width: 50%;
}
.info-img img{
    width: 500px;
    height: 250px;
}
.info-txt{
    width: 50%;
}
.info-txt h2{
    font-size: 75px;
    color: #ffffff;
    font-weight: 800;
    text-transform: uppercase;
    margin-bottom: 25px;
}
.info-txt p {
    font-size: 18px;
    color: #a7a7a7;
    margin-bottom: 50px;
}

.btn-2{
    display: inline-block;
    padding: 15px 35px;
    border: 2px solid #DB2418;
    color: #ffffff;
    font-weight: 800;
    letter-spacing: 2px;
    text-transform: uppercase;
    border-radius: 50px;
}
.btn-2:hover{
    background-color: #DB2418;
}




.horario{
    padding: 180px 0px;
    background-color: #0d0d0d;
}
.horario-info h2{
    font-size: 75px;
    color: #ffffff;
    text-transform: uppercase;
    margin-bottom: 50px;
}
.horario-txt{
    display: flex;
    justify-content: space-between;

}
.txt{
    color: #ffffff;
}
.txt h4{
    font-size: 18px;
    color: #a7a7a7;
    margin-bottom: 30px;
}
.txt p{
    font-size: 18px;
    text-transform: uppercase;
    font-weight: 600;
    margin-bottom: 15px;
}


.map{
    filter: grayscale(100%) invert(92%) contrast(93%);
}



.footer{
    padding: 100px 0px;
    display: flex;
    justify-content: space-between;
}

.links h4{
    color: #ffffff;
    text-transform: uppercase;
    margin-bottom: 25px;
}

.links ul li a{
    color: #ffffff;
    font-size: 16px;
    margin-bottom: 5px;
    display: inline-block;
}

@media(max-width: 991px){
    .menu{
        padding: 20px;
        justify-content: space-between;
    }
    .menu-2{
        display: none;
    }
    .logo-1{
        width: 100px;
    }
    .log-2{
        width: 0;
    }
    .menu label{
        display: initial;
    }
    .menu .navbar{
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background-color: #181818;
        display: none;
    }
    .menu ,.navbar ul li{
        width: 100%;
    }

    #menu:checked ~ .navbar{
        display: initial;
    }
    .header-content{
        padding: 30px;
        margin-top: 100px;
    }
    .slider{
        flex-direction: column;
    }
    .slider-txt{
        margin-left: 0;
        width: 100%;
        text-align: center;
        margin-bottom: 50px;
    }
    .slider-txt h1{
        font-size: 50px;
    }
    .slider-txt p{
        font-size: 16px;
    }
    .btn-1{
        padding: 10px 25px;
        font-size: 14px;
    }
    .slider-img{
        width: 100%;
        text-align: center;
    }
    .slider-img img{
        margin-right: 0px;
        width: 300px;
    }
    .swiper-horizontal > .swiper-pagination-bullets,
    .swiper-pagination-bullets,.swiper-pagination-horizontal,
    .swiper-pagination-custom,
    .swiper-pagination-fraction{
        bottom: -7px;;
    }

    .tabs{
        padding: 50px 30px;
    }
    .tabs label{
        width: 33%;
    }
    .info{
        padding: 30px;
        flex-direction: column;
    }
    .info-img{
        width: 100%;
        text-align: center;
    }
    .info-img img{
        width: 400px;
        height: 200px;
        margin-bottom: 25px;
    }
    .info-txt{
        width: 100%;
        text-align: center;
    }
    .info-txt h2{
        font-size: 50px;
    }
    .info-txt p{
        font-size: 16px;
    }
    .btn-1{
        font-size: 16px;
    }
    .horario{
        padding: 30px;
        text-align: center;
    }
    .horario-info h2{
        font-size: 50px;
        margin-bottom: 15px;
    }
    .horario-txt{
        flex-direction: column;
    }
    .social{
        justify-content: center;
    }
    .social img{
        margin: 8px 0 0 0;
    }
    .footer{
        padding: 30px;
        flex-direction: column;
        text-align: center;
    }
    .links h4{
        margin: 25px 0px 10px;

    }
}

var swiper = new Swiper(".mySwiper-1",{
    slidesPerView:1,
    spaceBetween: 30,
    loop:true,
    pagination: {
        el: ".swiper-pagination",
        clickable: true,
    },
    navigation:{
        nextE1:".swiper-button-next",
        prevE1:".swiper-button-prev",
    }
});

var swiper = new Swiper(".mySwiper-2",{
    slidesPerView:3,
    spaceBetween: 20,
    loop:true,
    loopFillGroupWithBlank:true,
    navigation: {
        nextE1:".swiper-button-next",
        prevE1:".swiper-button-prev",
    },
    breakpoints : {
        0:{
            slidesPerView:1,
        },
        520:{
            slidesPerView:2,
        },
        950:{
            slidesPerView:3,
        }
    }
});

let tabInputs = document.querySelectorAll(".tabInput");

tabInputs.forEach(function(input){
    input.addEventListener('chage', function(){
        let id = input.ariaValueMax;
        let thisSwiper= document.getElementById('swiper' + id);
        thisSwiper.swiper.update();
    })
});




                
            </div>
        </div>
    </footer>

    <script src="https://cdn.jsdeliver.net/npm/swiper-bundle.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
