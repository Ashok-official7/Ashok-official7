<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="Web.css">
    <script src="https://kit.fontawesome.com/f30fac2c61.js" crossorigin="anonymous"></script>
    <link
        href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Catamaran:wght@200&family=Courgette&family=Edu+TAS+Beginner:wght@700&family=Lato:wght@300;900&family=Mukta:wght@700&family=Mulish:wght@300&family=Open+Sans&family=PT+Sans:ital,wght@1,700&family=Poppins:wght@300&family=Raleway:wght@100&family=Roboto&family=Roboto+Condensed:wght@700&family=Roboto+Slab&display=swap"
        rel="stylesheet">
</head>

<body>
    <div class="container">
        <nav>
            <div class="logo">
                <h1>Trends</h1>
            </div>
            <ul>
                <li>
                    <a id="home" onclick="homes()">Home</a>
                    <a id="dg" onclick="shops()">DG</a>
                    <a id="infinity" onclick="blogs()">Infinity </a>
                    <a id="zafeera" onclick="abouts()">zafeera</a>
                    <a id="ams"
onclick="abouts()">Ams</a>
                    <a id="about"
onclick="abouts()">About</a>
                    <a id="contact"
                     onclick="contacts()">Contact</a>
                    <i class="fa-sharp fa-solid fa-cart-shopping"></i>

                </li>
            </ul>
        </nav>

        <!-- mainpage -->

        <div class="main">
            <div class="mainText">
                <h2>font</h2>
                <h1 class="top">calligraphy Fonts</h1>
                <h1>On All fonts</h1>
                <p> All packages And All calligraphy font in official website </p>
                <button>Explore</button>
            </div>
            <img src="content://com.android.providers.media.documents/document/image%3A1000008293" alt="">
        </div>

        <!-- cards -->

        <div class="trend">
            <div class="head">
                <h1>Trends <span>DG Fonts</span></h1>
            </div>
            <div class="card">
                <div class="crd">
                    <img src="srt1.webp" alt="" onclick="show(this)">
                    <div class="crdText">
                        <h2>Calligraphy Trending Font</h2>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half-stroke"></i> <br>
                        <button>Add to Cart</button>
                    </div>
                 </div>

                 <div class="crd">
                    <img src="srt2.webp" alt="" onclick="show(this)">
                    <div class="crdText">
                        <h2>Cutton Trending Shirt's</h2>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star"></i>
                        <i class="fa-solid fa-star-half-stroke"></i> <br>
                        <button>Add to Cart</button>
                    </div>
                 </div>
                    <div class="crd">
                        <img src="srt6.webp" alt="" onclick="show(this)">
                        <div class="crdText">
                            <h2>Cutton Trending Shirt's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>

                <!-- Women Card -->

                <div class="trend" id="trendSec">
                    <div class="head">
                        <h1>Trends <span>Women's Wear</span></h1>
                    </div>
                    <div class="card">
                        <div class="crd">
                            <img src="wn4.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>

                        <div class="crd">
                            <img src="wn5.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>

                        <div class="crd">
                            <img src="wn6.webp" alt="" onclick="show(this)">
                            <div class="crdText">
                                <h2>Trending Girl Top's</h2>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star-half-stroke"></i> <br>
                            <button>Add to Cart</button>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- about us -->

                <div class="about">

                    <div class="aboutus">
                        <h1>#KnowUs</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>

                    <div class="me">
                        <img src="lap.png" alt="">
                        <div class="aboutText">
                            <h1>Who we are ?</h1>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing Dolorum corrupti consequuntur sunt ipsam aperiam vel magni sequi eos sit amet consectetur adipisicing Dolorum corrupti consequuntur sunt ipsam aperiam vel magni sequi eos atque nam maxime dolorem fuga, rem eum iure quidem! Illo corporis, asperiores ipsum excepturi voluptates necessitatibus consectetur odit omnis hic praesentium autem, officiis dignissimos assumenda saepe.</p>
                        </div>
                    </div>
                </div>

                <!-- contact -->

                <div class="contact">

                    <div class="contactus">
                        <h1>#Let's Connect</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>

                    <div class="contactMe">
                        <div class="contactText">
                            <h1>Visit Our Office or Contact <br>
                                Us Today</h1>
                            <p>Address : Dablin Park, England, New york.</p>
                            <p>Contact : dumiemail@gmail.com</p>
                            <p>Number : 999999000011</p>
                        </div>
                        <img src="map.PNG" alt="">
                    </div>

                    <div class="form">
                        <h1>Connect with Us. Fill Form</h1>
                        <input type="text" placeholder="Enter Email"> <br>
                        <input type="text" placeholder="Enter Email"> <br>
                        <input type="text" placeholder="Enter Email"> <br>
                        <input type="text" placeholder="Enter Email"> <br>
                        <input type="text" placeholder="Enter Email"> <br>
                        <button>Submit</button>

                    </div>
                </div>
                 <!-- cart -->

                 <div class="cart">
                    <img id="newImg" src="" alt="">
                    <div class="cartText">
                        <h1>Trends Offer : Trending Shop <br>
                            Now</h1>
                            <h2>Special Price</h2>
                            <h2>$11</h2>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing.</p>
                           <div class="btn">
                            <button>Buy Now</button>
                            <button onclick="addCart()">Add to Cart</button>
                           </div>
                           <button  class="back">Back</button>



                    </div>
                 </div>

                <!-- blogs -->
                <div class="trends">
                    <div class="head">
                        <h1>Trends <span>Men's Wear</span></h1>
                    </div>
                    <div class="card">
                        <div class="blog">
                            <img src="tr1.webp" alt="">
                            <div class="blogText">
                                <h2>Trending Girl Cloths</h2>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem, animi expedita?</p>
                                <a href="https://influencermarketinghub.com/best-fashion-blogs/">Read More</a>
                            </div>
                        </div>

                        <div class="blog">
                            <img src="tr3.webp" alt="">
                            <div class="blogText">
                                <h2>Trending Boys Cloths</h2>
                                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem, animi expedita?</p>
                                <a href="https://www.apetogentleman.com/">Read More</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Letter -->

                <div class="letter">
                    <div class="letterText">
                        <h1>Sign Up for NewsLetter</h1>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="inp">
                        <input type="text" placeholder="Enter Email">
                        <button>Sign Up</button>
                    </div>
                </div>

                <!-- Footer -->

                <div class="footer">
                    <div class="footerText">
                        <h2>Trends</h2>
                        <p>Service </p>
                        <p>Customer</p>
                        <p>Satisfaction</p>
                        <p></p>

                    </div>
                    <div class="footerText">
                        <h2>About US</h2>
                        <p>Adrress : Lorem ipsum dolor sit amet, <br>
                            consectetur adipisicing <br>
                            Perferendis, excepturi alias.</p>
                        <p>Service</p>
                        <p>Customer</p>
                        <p>Satisfation</p>

                    </div>
                    <div class="footerText">
                        <h2>Contect</h2>
                        <p>9989003229</p>
                        <p>Customer</p>
                        <p>Comming up</p>
                        <p>New Arrival</p>

                    </div>
                    <div class="footerText">
                        <h2>Trending</h2>
                        <p>Service</p>
                        <p>Customer</p>
                        <p>Shops</p>
                        <p></p>

                    </div>
                </div>
            </div>
            <script src="Web.js"></script>
</body>

</html
