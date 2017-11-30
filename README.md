# Omnifood
Portfolio Piece FoodGallery

HTML SECTION

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" type="text/css" href="vendors/c  ss/normalize.css">
        <link rel="stylesheet" type="text/css" href="vendors/css/grid.css">
        <link rel="stylesheet" type="text/css" href="vendors/css/ionicons.min.css">
        <link rel="stylesheet" type="text/css" href="vendors/css/animate.css">
        <link rel="stylesheet" type="text/css" href="css/thekillerwebsite.css">
        <link rel="stylesheet" type="text/css" href="css/responsive.css">
        <link href="https://fonts.googleapis.com/css?family=Lato:100,300,300i,400" rel="stylesheet">
        
        <title>Bitchin!</title> 
    </head>
    <body>
        <header>
            <nav>
                <div class="row">
                   <img src="resources/img/logo-white.png" alt="Omnifood Logo" class="logo">
                   <img src="resources/img/logo.png" alt="Omnifood Logo" class="logo-black">
                    <ul class="main-nav js--main-nav">
                        <li><a href="#features">Food delivery</a></li>
                        <li><a href="#works">How it works</a></li>
                        <li><a href="#cities">Our cities</a></li>
                        <li><a href="#plans">Sign up</a></li>
                    </ul>   
                    <a class="mobile-nav-icon js--nav-icon"><i class = "ion-navicon-round"></i></a>
                </div>
            </nav>
            <div class="hero-text-box">
                <h1>Goodbye junk food.<br> Hello super healthy meals.</h1>
                <a class = "btn btn-full js--scroll-to-plans" href="#">I’m hungry</a>
                <a class = "btn btn-ghost js--scroll-to-start" href="#">Show me more</a>
            </div>
        </header>
        
        <section class="section-features js--section-features" id="features">
            <div class="row">
                <h2>Get food fast &mdash; not fast food.</h2>
                <p class="long-copy">
                    Hello, we're Omnifood, your new premium food delivery service. We know you’re always busy. No time for cooking. So let us take care of that, we’re really good at it, we promise!
                </p>
            </div>
            <div class="row js--wp-1">
                <div class="col span-1-of-4 box">
                    <i class="ion-ios-infinite-outline icon-big"></i>
                    <h3>Up to 365 days/year</h3>
                    <p>
                        Never cook again! We really mean that. Our subscription plans include up to 365 days/year coverage. You can also choose to order more flexibly if that's your style.
                    </p>
                </div>
                <div class="col span-1-of-4 box">
                    <i class="ion-ios-stopwatch-outline icon-big"></i>
                    <h3>Ready in 20 minutes</h3>
                    <p>
                        You're only twenty minutes away from your delicious and super healthy meals delivered right to your home. We work with the best chefs in each town to ensure that you're 100% happy.
                    </p>
                </div>
                <div class="col span-1-of-4 box ">
                    <i class="ion-ios-nutrition-outline icon-big"></i>
                    <h3>100% organic</h3>
                    <p>
                        All our vegetables are fresh, organic and local. Animals are raised without added hormones or antibiotics. Good for your health, the environment, and it also tastes better!
                    </p>
                </div>
                <div class="col span-1-of-4 box">
                    <i class="ion-ios-cart-outline icon-big"></i>
                    <h3>Order anything</h3>
                    <p>
                        We don't limit your creativity, which means you can order whatever you feel like. You can also choose from our menu containing over 100 delicious meals. It's up to you!
                    </p>
                </div>
            </div>
        </section>
        <section class="section-meals">
            <ul class="meals-showcase clearfix">
                <li>
                    <figure class="meal-photo">
                        <img src="resources/img/1.jpg" alt="Korean bibimbap with egg and vegetables">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/2.jpg" alt="Simple italian pizza with cherry tomatoes">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/3.jpg" alt="Chicken breast steak with vegetables">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/4.jpg" alt="Autumn pumpkin soup">
                    </figure>
                </li>
            </ul>
            <ul class="meals-showcase clearfix">
                <li>
                    <figure class="meal-photo">
                        <img src="resources/img/5.jpg" alt="Paleo beef steak with vegetables">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/6.jpg" alt="Healthy baguette with egg and vegetables">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/7.jpg" alt="Burger with cheddar and bacon">
                    </figure>
                </li><li>
                    <figure class="meal-photo">
                        <img src="resources/img/8.jpg" alt="Granola with cherries and strawberries">
                    </figure>
                </li>
            </ul>
        </section>
        <section class="section-steps" id="works">
            <div class="row">
                <h2>How it works &mdash; Simple as 1, 2, 3</h2>
            </div>
            <div class="row">
                <div class="col span-1-of-2 steps-box">
                    <img src="resources/img/app-iPhone.png" alt="Ominifood app on I-phone" class="app-screen js--wp-2">
                </div>
                <div class="col span-1-of-2 steps-box">
                    <div class="works-step">
                        <div>1</div>
                        <p>Choose the subscription plan that best fits your needs and sign up today.</p>
                    </div><div class="works-step">
                        <div>2</div>
                        <p>Order your delicious meal using our mobile app or website. Or you can even call us!</p>
                    </div><div class="works-step">
                        <div>3</div>
                        <p>Enjoy your meal after less than 20 minutes. See you the next time!</p>
                    </div>
                    
                    <a href="#" class="btn-app"><img src ="resources/img/download-app.svg" alt = "App Store Button"></a><a href="#" class="btn-app"><img src ="resources/img/download-app-android.png" alt = "Play Store"></a>
                    
                </div>
            </div>
        </section>
        <section class="section-cities" id="cities">
            <div class="row">
               <h2>We're currently in these cities</h2> 
            </div>
            <div class="row js--wp-3">
                <div class="col span-1-of-4 box">
                    <img src="resources/img/lisbon-3.jpg" alt="Lisbon">
                    <h3>Libson</h3>
                    <div class="city-feature">
                        <i class="ion-ios-person icon-small"></i>
                        1600+ happy eaters
                    </div>
                    <div class="city-feature">
                        <i class="ion-ios-star icon-small"></i>
                        60+ top chefs
                    </div>
                    <div class="city-feature">
                        <i class="ion-social-twitter icon-small"></i>
                        <a href="#">@omnifood_lx</a>
                    </div>
                </div>
                <div class="col span-1-of-4 box">
                    <img src="resources/img/san-francisco.jpg" alt="San-Fransisco">
                    <h3>San Fransisco</h3>
                    <div class="city-feature">
                        <i class="ion-ios-person icon-small"></i>
                        3700+ happy eaters
                    </div>
                    <div class="city-feature">
                        <i class="ion-ios-star icon-small"></i>
                        160+ top chefs
                    </div>
                    <div class="city-feature">
                        <i class="ion-social-twitter icon-small"></i>
                       <a href="#">@omnifood_sf</a>
                    </div>
                </div>
                <div class="col span-1-of-4 box">
                    <img src="resources/img/berlin.jpg" alt="Berlin">
                    <h3>Libson</h3>
                    <div class="city-feature">
                        <i class="ion-ios-person icon-small"></i>
                        2300+ happy eaters
                    </div>
                    <div class="city-feature">
                        <i class="ion-ios-star icon-small"></i>
                        110+ top chefs
                    </div>
                    <div class="city-feature">
                        <i class="ion-social-twitter icon-small"></i>
                        <a href="#">@omnifood_berlin</a>
                    </div>
                </div>
                <div class="col span-1-of-4 box">
                    <img src="resources/img/london.jpg" alt="London">
                    <h3>Libson</h3>
                    <div class="city-feature">
                        <i class="ion-ios-person icon-small"></i>
                        1200+ happy eaters
                    </div>
                    <div class="city-feature">
                        <i class="ion-ios-star icon-small"></i>
                        50+ top chefs
                    </div>
                    <div class="city-feature">
                        <i class="ion-social-twitter icon-small"></i>
                        <a href="#">@omnifood_london</a>
                    </div>
                </div>
            </div>
        </section>
        <section class="section-testimonials">
            <div class="row">
                <h2>Our customers can't live without us</h2>
            </div>
            <div class="row">
                <div class="col span-1-of-3">
                    <blockquote>
                    Omnifood is just awesome! I just launched a startup which leaves me with no time for cooking, so Omnifood is a life-saver. Now that I got used to it, I couldn't live without my daily meals!
                    <cite><img src="resources/img/customer-1.jpg">Alberto Duncan</cite>
                    </blockquote>
                </div>
                <div class="col span-1-of-3">
                    <blockquote>
                    Inexpensive, healthy and great-tasting meals, delivered right to my home. We have lots of food delivery here in Lisbon, but no one comes even close to Omifood. Me and my family are so in love!
                    <cite><img src="resources/img/customer-2.jpg">Joana Silva</cite>
                    </blockquote>
                </div>
                <div class="col span-1-of-3">
                    <blockquote>
                    I was looking for a quick and easy food delivery service in San Franciso. I tried a lot of them and ended up with Omnifood. Best food delivery service in the Bay Area. Keep up the great work!
                    <cite><img src="resources/img/customer-3.jpg">Milton Chapman</cite>
                    </blockquote>
                </div>
            </div>
        </section>
        <section class="section-plans js--section-plans" id="plans">
            <div class="row">
                <h2>Start eating healthy today</h2>
            </div>
            <div class="row">
                <div class="col span-1-of-3">
                    <div class="plan-box js--wp-4">
                        <div>
                            <h3>Premium</h3>
                            <p class="plan-price">$399 <span>/ month</span></p>
                            <p class="plan-price-meal">That’s only 13.30$ per meal</p>
                        </div>
                        <div>
                            <ul>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>1 meal every day</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Order 24/7</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Access to newest creations</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Free delivery</li>
                            </ul>
                        </div>
                        <div>
                            <a href="#" class="btn btn-full">Sign up now</a>
                        </div>
                    </div>
                </div>
                    
                    <div class="col span-1-of-3">
                    <div class="plan-box">
                        <div class="">
                            <h3>Pro</h3>
                            <p class="plan-price">$149 <span>/ month</span></p>
                            <p class="plan-price-meal">That’s only 14.90$ per meal</p>
                        </div>
                        <div class="">
                            <ul>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>1 meal 10 days/month</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Order 24/7</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Access to newest creations</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Free delivery</li>
                            </ul>
                        </div>
                        <div class="">
                            <a href="#" class="btn btn-ghost">Sign up now</a>
                        </div>
                    </div>
                </div>
                    
                    <div class="col span-1-of-3">
                    <div class="plan-box">
                        <div class="">
                            <h3>Starter</h3>
                            <p class="plan-price">$19 <span>/ meal</span></p>
                            <p class="plan-price-meal">&nbsp;</p>
                        </div>
                        <div class="">
                            <ul>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>1 meal every day</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Order from 8 am to 12 pm</li>
                                <li><i class = "ion-ios-close-empty icon-small"></i>Access to newest creations</li>
                                <li><i class = "ion-ios-checkmark-empty icon-small"></i>Free delivery</li>
                            </ul>
                        </div>
                        <div class="">
                            <a href="#" class="btn btn-ghost">Sign up now</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section-form">
            <div class="row">
                <h2>We're happy to hear from you</h2>
            </div>
            <div class="row">
                <form method="post" action="#" class="contact-form">
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label for="name">Name</label>
                        </div>
                        <div class="col span-2-of-3">
                            <input type="text" name="name" id="name" placeholder="Your Name" required>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label for="email">Email</label>
                        </div>
                        <div class="col span-2-of-3">
                            <input type="email" name="email" id="email" placeholder="Your Email" required>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label for="find-us">How did you find us?</label>
                        </div>
                        <div class="col span-2-of-3">
                            <select name="find-us" id="find-us">
                                <option value="friends selected">Friends</option>
                                <option value="search" >Search Engine</option>
                                <option value="ad">Advertisement</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label>Newsletter</label>
                        </div>
                        <div class="col span-2-of-3">
                            <input type="checkbox" name="news" id="news" checked> Yes, please
                        </div>
                    </div>
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label>Drop us a line</label>
                        </div>
                        <div class="col span-2-of-3">
                            <textarea name="message" placeholder="Your Message"></textarea>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col span-1-of-3">
                            <label>&nbsp;</label>
                        </div>
                        <div class="col span-2-of-3">
                            <input type="submit" value="Send it!">
                        </div>
                    </div>
                </form>
            </div>
        </section>
        <footer>
            <div class="row">
                <div class="col span-1-of-2">
                    <ul class="footer-nav">
                        <li><a href="#">About us</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Press</a></li>
                        <li><a href="#">iOS App</a></li>
                        <li><a href="#">Android App</a></li>
                    </ul>
                </div>
                <div class="col span-1-of-2">
                    <ul class="social-links">
                        <li><a href ="#"><i class ="ion-social-facebook"></i></a></li>
                        <li><a href ="#"><i class ="ion-social-twitter"></i></a></li>
                        <li><a href ="#"><i class ="ion-social-googleplus"></i></a></li>
                        <li><a href ="#"><i class ="ion-social-instagram"></i></a></li>
                    </ul>
                </div>
            </div>
            <div class="row">
                <p>Copyright &copy; 2017 by Omnifood. All Rights Reserved</p>
            </div>
        </footer>
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
        <script src="vendors/js/jquery.waypoints.min.js"></script>
        <script src="resources/js/killerwebsite.js"></script>
        
<!--
    <script src="//cdn.jsdelivr.net/respond/1.4.2/respond.min.js"></script>
    <script src="//cdn.jsdelivr.net/html5shiv/3.7.2/html5shiv.min.js"></script>
    <script src="//cdn.jsdelivr.net/selectivizr/1.0.3b/selectivizr.min.js"></script>
-->  
        
    </body>
    
</html>

CSS SECTION 

/*Website Reusable Color*/
/*#e67e22;*/
/*-----------------------------------*/
/*Basic Set Up*/
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html,
body
    {
    background-color: #fff;
    color: #555;
    font-family: 'Lato', 'Arial', sans-serif;
    font-weight: 300;
    font-size: 20px;
    text-rendering: optimizeLegibility;
    overflow-x: hidden;
}
.clearfix {zoom:1}
.clearfix:after{
    content: '.';
    clear: both;
    display: block;
    height: 0;
    visibility: hidden;
}
/*------------------------------------------*/
/*Reusable Components*/
/*------------------------------------------*/
.row{
    max-width: 1140px;
    margin: 0 auto;
}
.box{
    padding: 1%;
}
section{
    padding: 80px 0;
}
/*Headings*/
h1, 
h2,
h3{
    text-transform: uppercase;
    font-weight: 300;
    
}
h1{
    margin-top: 0;
    margin-bottom: 20px;
    color: #fff;
    font-size: 240%;
    word-spacing: 4px;
    letter-spacing: 1px;
}
h2{
    font-size: 180%;
    word-spacing: 2px;
    text-align: center;
    margin-bottom: 30px;
    letter-spacing: 1px;
}
h3{
    font-size: 110%;
    margin-bottom: 15px;
}
h2:after{
    display: block;
    height: 2px;
    background-color: #e67e22;
    content: " ";
    width: 100px;
    margin: 0 auto;
    margin-top: 30px;
}
/*Paragraphs*/
.long-copy{
    line-height: 145%;
    width: 70%;
    margin-left: 15%;
}
.box p{
    font-size: 90%;
    line-height: 145%;
}
/*Icons*/
.icon-big{
    font-size: 350%;
    display: block;
    color: #e67e22;
    margin-bottom: 10px;
}
.icon-small{
    display: inline-block;
    width: 30px;
    text-align: center;
    color: #e67e22;
    font-size: 120%;
    margin-right: 10px;
/*Secrets to align text and icons*/
    line-height: 120%;
    vertical-align:middle;
    margin-top: -5px;

}
/*Links*/
a:link,
a:visited{
    color: #e67e22; 
    text-decoration: none;
    border-bottom: 1px solid #e67e22; 
    padding-bottom: 1px;
    transition: border-bottom .3s, color .3s;
}
a:hover,
a:active{
   color: #555; 
    border-bottom: 1px solid transparent; 
}
/*Buttons*/
.btn:link,
.btn:visited,
input[type=submit]{
    display: inline-block;
    padding: 10px 30px;
    font-weight: 300;
    text-decoration: none;
    border-radius: 200px;
    transition: background-color .3s, border .3s, color .3s;
}
.btn-full:link,
.btn-full:visited,
input[type=submit]{
    background-color: #e67e22;
    border: 1px solid #e67e22;
    color: #fff;
    margin-right: 15px;
}
.btn-ghost:link,
.btn-ghost:visited{
    border: 1px solid #e67e22;
    color: #e67e22;
}
.btn:hover,
.btn:active,
input[type=submit]:hover,
input[type=submit]:active{
    background-color: #cf6d17;
}
.btn-full:hover,
.btn-full:active,
input[type=submit]{
    border: 1px solid #cf6d17;
}
.btn-ghost:hover,
.btn-ghost:active{
    border: 1px solid #e67e22;
    color: #fff;
}
/*------------------------------------------*/
/*Header*/
/*------------------------------------------*/
header{
    background-image:linear-gradient(rgba(0, 0, 0, 0.67), rgba(0, 0, 0, 0.7)), url(img/hero.jpg);
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    
}
.hero-text-box{
    position: absolute;
    width: 1140px;
    top: 50%;
    left:50%;
    transform: translate(-50%, -50%);
    
}
.logo
    {
    height: 100px;
    width: auto;
    float: left;
    margin-top: 20px;
}
.logo-black{
    display: none;
    height: 50px;
    width: auto;
    float: left;
    margin: 5px 0 ;
}
/*Main Nav*/
.main-nav{
    float: right;
    list-style: none;
    margin-top: 55px;
}
.main-nav li{
    display: inline-block;
    margin-left: 40px;
}
.main-nav li a:link,
.main-nav li a:visited
    {
    padding: 8px 0;
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 90%;
    border-bottom: 2px solid transparent;
    transition: border-bottom .2s;
}
.main-nav li a:hover,
.main-nav li a:visited{
    border-bottom: 2px solid #e67e22;
}
/*Mobile Nav*/
.mobile-nav-icon{
    float: right;
    margin-top: 30px;
    cursor: pointer;
    display: none;
}
.mobile-nav-icon i{
    font-size: 200%;
    color: #fff;
}
/*Sticky Nav*/
.sticky{
    position: fixed;
    top:0;
    left: 0;
    width: 100%;
    background-color: rgba(255, 255, 255, 0.96);
    box-shadow: 0 2px 2px #efefef;
    z-index: 9999;
}  
.sticky .main-nav{margin-top: 18px;}
.sticky .main-nav li a:link,
.sticky .main-nav li a:visited
    {
    padding: 16px 0;
    color: #555;
}
.sticky .logo {
    display: none;
}
.sticky .logo-black {
    display:block;
}
/*------------------------------------------*/
/*Features*/
/*------------------------------------------*/
.section-features .long-copy{
    margin-bottom: 30px;
}
/*------------------------------------------*/
/*Meals*/
/*------------------------------------------*/
.section-meals{
    padding: 0;
}
.meals-showcase{
    list-style: none;
    width: 100%;
}
.meals-showcase li{
    display: block;
    float: left;
    width: 25%;
}
.meal-photo{
    width: 100%;
    margin: 0;
    overflow: hidden;
    background-color: #000;
}
.meal-photo img{
    opacity: 0.7;
    width: 100%;
    height: auto;
    transform: scale(1.15);
    transition: transform 0.5s,opacity 0.5s;
}
.meal-photo img:hover{
    opacity: 1;
    transform:  scale(1.03);
}
/*------------------------------------------*/
/*How It Works*/
/*------------------------------------------*/
.section-steps{
    background-color: #f4f4f4;
}
.steps-box:first-child{
    text-align: right;
    padding-right: 3%;
}
.steps-box:last-child{
    padding-left: 3%;
    margin-top: 70px;
}
.app-screen{
    width: 40%;
}
.works-step{
    margin-bottom: 50px;
}
.works-step:last-of-type{
    margin-bottom: 80px;
}
.works-step div{
    color: #e67e22;
    border: 2px solid #e67e22;
    display: inline-block;
    border-radius: 50%;
    height: 50px;
    width: 55px;
    text-align: center;
    padding: 5px;
    float: left;
    font-size: 150%;
    margin-right: 25px;
}
.btn-app:link,
.btn-app:visited{
    border: 0;
}
.btn-app img{
    height: 50px;
    width: auto;
    margin-right: 10px;
}
/*------------------------------------------*/
/*Cities*/
/*------------------------------------------*/
.box img{
    width: 100%;
    height: auto;
    margin-bottom: 15px;
}
.city-feature{
    margin-bottom: 5px;
}
/*------------------------------------------*/
/*Testimonials*/
/*------------------------------------------*/
.section-testimonials{
    background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url(img/back-customers.jpg);
    background: cover;
    color: #fff;
    background-attachment: fixed;
    
}
blockquote{
    padding: 2%;
    font-style: italic;
    line-height: 145%;
    position: relative;
    margin-top: 40px;
}
blockquote:before{
    content: "\201C";
    font-size: 500%;
    display: block;
    position: absolute;
    top: -5px;
    left: -3;
}
cite{
    font-size: 90%;
    margin-top: 25px;
    display: block;
}
cite img{
    height: 45px;
    border-radius: 50%;
    margin-right: 10px;
    vertical-align: middle;
}
/*------------------------------------------*/
/*Sign Up*/
/*------------------------------------------*/
.section-plans{
    background-color: #f4f4f4;
}
.plan-box{
    background-color: #fff;
    border-radius: 5px;
    width: 90%;
    margin-left: 5%;
    box-shadow: 0 3px 3px #efefef;
}
.plan-box div{
    padding: 15px;
    border-bottom: 1px solid #e8e8e8;
}
.plan-box div:first-child{
    background-color:#fcfcfc;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
}
.plan-box div:last-child{
    text-align: center;
    border: 0;
}
.plan-price{
    font-size: 300%;
    margin-bottom: 10px;
    font-weight: 100;
    color: #e67e22;
}
.plan-price span{
   font-size: 30%; 
    font-weight: 300;
}
.plan-price-meal{
    font-size: 80%;  
}
.plan-box ul{
    list-style: none;
}
.plan-box ul li{
    padding: 5px 0;
}
/*------------------------------------------*/
/*Sign Up*/
/*------------------------------------------*/
.contact-form{
    width: 60%;
    margin: 0 auto;    
}
input[type=text],
input[type=email],
select,
textarea{
    width: 100%;
    padding: 7px;
    border-radius: 3px;
    border: 1px solid #ccc;
}
textarea{
    height: 100px;
}
input[type=checkbox]{
    margin: 10px 5px 10px 0;
}
*:focus{
    outline: none;
}
footer{
    background-color: #333;
    padding: 50px;
    font-size: 80%;
}
footer nav{
    list-style: none;
    float: left;
}
.social-links{
    list-style: none;
    float: right;
}
.footer-nav li,
.social-links li{
    display: inline-block;
    margin-right: 20px;
}
.footer-nav li:last-child,
.social-links li:last-child{
    margin: 0;
}
.footer-nav li a:link,
.footer-nav li a:visited,
.social-links li a:link,
.social-links li a:visited{
    text-decoration: none;
    border: none;
    color: #888;
    transition: color 0.3s;
}
.footer-nav li a:hover,
.footer-nav li a:active{
    color: #ddd;
}
.social-links li a:link,
.social-links li a:visited{
    font-size: 160%;
}
.ion-social-facebook,
.ion-social-twitter,
.ion-social-googleplus,
.ion-social-instagram{
    transition: color .3s;
}
.ion-social-facebook:hover{
    color: #3b5998;
}
.ion-social-twitter:hover{
    color: #00aced;
}
.ion-social-googleplus:hover{
    color: #dd4b39;
}
.ion-social-instagram:hover{
    color: #517fa4;
}
footer p{
    color: #888;
    text-align: center;
    margin-top:20px;
}
/*------------------------------------------*/
/*Animations*/
/*------------------------------------------*/
.js--wp-1,
.js--wp-2,
.js--wp-3
{
    opacity: 0;
    animation-duration: 1s;
}
.js-wp-4{
    animation-duration: 2s;
}
.js--wp-1 .animated,
.js--wp-2 .animated,
.js--wp-3 .animated{
    opacity: 1;
}
RESPONSIVE CSS SECTION

/*Big tablet to 1200px(widths smaller than the 1140px row)*/
@media only screen and (max-width:1200px) {
    .hero-text-box {
        width: 100%;
        padding: 0 2%;
    }
    .row{
      padding: 0 2%;  
    }
}
/*Small tablet to big tablet: fron 768px to 1023px*/
@media only screen and (max-width:1023px) { 
    body{font-size: 18px;}
    section{padding: 60px 0;}
    .long-copy{
        width: 80%;
        margin-left: 10%;
    }
    .steps-box{margin-top:10px;}
    .steps-box:last-child{margin-top:10px;}
    .works-steps{margin-bottom: 40px;}
    .works-steps:last-of-type{margin-bottom: 80px;}
    .app-screen{width: 50%;}
    .icon-small{
        width: 17px;
        margin-right: 5px;
    }
    .city-features{font-size: 90%;}
    .plan-box{
        width: 100%;
        margin-left: 0;
    }
    .plan-price{font-size: 350%;}
    .contact-form{width: 80%;}
    
}
/*Small phones to small tablets: 481 to 767px*/

@media only screen and (max-width:767px) {  

    body{
        font-size: 16px;
    }
    section{
        padding: 30px 0;
    }
    .row,
    .hero-text-box{
        padding: 0 4%;
    }


    .col{
        width: 100%;
        margin: 0% 0 4% 0%;
    }

    .main-nav{
        display: none;
    }

    .mobile-nav-icon{
        display: inline-block;
    }

    .main-nav{
        float: left;
        margin-top: 35px;
        margin-left: 25px;
    }



    .main-nav li{
        display: block;
    }


    .main-nav li a:link,
    .main-nav li a:visited{
        display: block;
        border: 0;
        padding: 10px 0;
        font-size: 100%;
    }

    .sticky .main-nav{
        margin-top: 10px;
    }
    .sticky .main-nav li a:link,
    .sticky .main-nav li a:visted{
        padding: 10px 0;
    }
    .sticky .mobile-nav-icon{
        margin-top: 10px;
    }
    .sticky .mobile-nav-icon i{
        color: #555;
    }


    
    h1{
        font-size: 180%;
    }
    h2{
        font-size: 150%;
    }
    .long-copy{
        width:100%;
        margin-left: 0%;
    }
    .app-screen{
        width: 40%;
    }
    .steps-box:first-child{
        text-align: center;
    }
    .works-steps div{
        height: 40px;
        width: 40px;
        margin-right: 15px;
        padding: 4px;
        font-size: 120%;
    }
    .works-step{
        margin-bottom: 20px;
    }
    .works-step:last-of-type{
        margin-bottom: 20px;
    }
}

Small Phones from 0 to 480px
@media only screen and (max-width:480px) {
    section{
        padding: 25px 0; 
    }
    .contact-form{
        width: 100%;
    }
}
JQUERY SECTION

$(document).ready(function() {
    /*For the Sticky Navigation*/
    $(".js--section-features").waypoint(function(direction){
        if (direction == "down") {
            $("nav").addClass("sticky");
        }
        else {
            $("nav").removeClass("sticky");
        }
    }, {
  offset: '60px;'
})
    /*Navigation Scroll*/
    
$('a[href*="#"]')
  // Remove links that don't actually link to anything
  .not('[href="#"]')
  .not('[href="#0"]')
  .click(function(event) {
    // On-page links
    if (
      location.pathname.replace(/^\//, '') == this.pathname.replace(/^\//, '') 
      && 
      location.hostname == this.hostname
    ) {
      // Figure out element to scroll to
      var target = $(this.hash);
      target = target.length ? target : $('[name=' + this.hash.slice(1) + ']');
      // Does a scroll target exist?
      if (target.length) {
        // Only prevent default if animation is actually gonna happen
        event.preventDefault();
        $('html, body').animate({
          scrollTop: target.offset().top
        }, 1000, function() {
          // Callback after animation
          // Must change focus!
          var $target = $(target);
          $target.focus();
          if ($target.is(":focus")) { // Checking if the target was focused
            return false;
          } else {
            $target.attr('tabindex','-1'); // Adding tabindex for elements not focusable
            $target.focus(); // Set focus again
          };
        });
      }
    }
  });
    /*Animations on Scroll*/
    $(".js--wp-1").waypoint(function(direction){
        $(".js--wp-1").addClass("animated fadeIn");
    }, {
        offset: "50%"
    });
    
    $(".js--wp-2").waypoint(function(direction){
        $(".js--wp-2").addClass("animated fadeInUp");
    }, {
        offset: "50%"
    });
    
    $(".js--wp-3").waypoint(function(direction){
        $(".js--wp-3").addClass("animated fadeIn");
    }, {
        offset: "50%"
    });
    
    $(".js--wp-4").waypoint(function(direction){
        $(".js--wp-4").addClass("animated pulse");
    }, {
        offset: "50%"
    });
    //Mobile Navigation
    $(".js--nav-icon").click(function() {
        var nav = $(".js--main-nav");
        var icon = $(".js--nav-icon i");
        
        nav.slideToggle(200);
        if (icon.hasClass("ion-navicon-round") ) {
            icon.addClass("ion-close-round");
            icon.removeClass("ion-navicon-round");
        }
        else {
            icon.addClass("ion-navicon-round");
            icon.removeClass("ion-close-round");
        }
        
    });
    
} );
