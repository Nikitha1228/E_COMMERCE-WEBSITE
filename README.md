<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>E-commerce</title>
    <link href="style.css" rel="stylesheet" type="text/css" />

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">

    <!-- fontawesome cdn For Icons -->
    <link rel="stylesheet"
     href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.0/css/all.min.css"
     integrity="sha512-PgQMlq+nqFLV4ylk1gwUOgm6CtIIXkKwaIHp/PAIWHzig/lKZSEGKEys
     h0TCVbHJXCLN7WetD8TFecIky75ZfQ=="
     crossorigin="anonymous" />

     <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

     <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">



  </head>
  <body>
    <script src="script.js"></script>
    <!-- ==============header menu section starts here============== -->
    <section class="header_menu" id="header_menu">
    <div class="container-fluid px-0 shadow">
    <nav class="navbar navbar-expand-lg navbar-light bg-light py-3 pt-4 pb-4">
    <a class="navbar-brand pl-5 pl-small-0" href="index.html">
    <img src="assets/images/logo.png" class="img img-fluid" width="100px" height="10px"
    alt="logo">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse"
    data-target="#navbarSupportedContent"
    aria-controls="navbarSupportedContent" aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mx-auto">
    <li class="nav-item active">
    <a class="nav-link" href="index.html">Home <span
    class="sr-only"></span></a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="product.html">Product</a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="category.html">Category</a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="about.html">About Us</a>
    </li>
    <li class="nav-item">
    <a class="nav-link" href="contact.html">Contact Us</a>
    </li>
<!-- <li class="nav-item dropdown">
<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown"
role="button" data-toggle="dropdown"
aria-haspopup="true" aria-expanded="false">
Dropdown
</a>
<div class="dropdown-menu" aria-labelledby="navbarDropdown">
<a class="dropdown-item" href="#">Action</a>
<a class="dropdown-item" href="#">Another action</a>
<div class="dropdown-divider"></div>
<a class="dropdown-item" href="#">Something else here</a>
</div>
</li> -->
</ul>
<div class="search mr-2">
<a href="search.html" class="btn btn-lg btn-outline-primary">
Search
</a>
</div>
<div class="cart">
<a href="cart.html">
<i class="fas fa-shopping-cart fa-2x"></i>
<span class="badge badge-pill badge-primary">cart</span>
</a>
</div>
</div>
</nav>
</div>
</section>
<!--<img src="assets/images/01.jpeg"
class="img img-fluid" alt="">-->

<section class="header_carousel" id="header_carousel">
<div id="carouselExampleInterval" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active" data-interval="10000">
      <img src="assets/images/01.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item" data-interval="2000">
      <img src="assets/images/02.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="assets/images/03.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="assets/images/04.jpeg" class="d-block w-100" alt="...">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleInterval" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleInterval" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</section>


<!-- ==============shop by category starts here============== -->
<section class="shop_by_category py-5 my-5" id="shop_by_category">
<div class="container-fluid">
<div class="section_title text-center mb-5">
<h1 class="text-capitalize">Shop By category</h1>
</div>
<div class="row">
<div class="col-md-4 col-12">
<div class="card bg-dark text-white">
<a href="category.html">
<img class="card-img img img-fluid" src="assets/images/category1.png"
alt="Card image">
</a>
</div>
</div>
<div class="col-md-4 col-12 mt-small-5 mb-small-5">
<div class="card bg-dark text-white">
<a href="category.html">
<img class="card-img img img-fluid" src="assets/images/category2.png"
alt="Card image">
</a>
</div>
</div>
<div class="col-md-4 col-12">
<div class="card bg-dark text-white">
<a href="category.html">
<img class="card-img img img-fluid" src="assets/images/category3.png"
alt="Card image">
</a>
</div>
</div>
</div>
</div>
</section>
<!-- ==============shop by category ends here============== -->



    <!-- ==============products starts here============== -->
<section class="products py-5 my-5 bg-light" id="products">
<div class="container ">
<div class="section_title text-center mb-5">
<h1 class="text-capitalize">Latest Products</h1>
</div>
<div class="row mb-5">
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product1.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">NEW</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<i class="fas fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">IPHONE 11 with details - 80,000</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>80,000</span></b>
</div>
</div>
</div>
</div>
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1 mt-small-5 mb-small-5">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product2.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">New</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">APPLE WATCH with details</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>25,000</span></b>
</div>
</div>
</div>
</div>
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product3.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">New</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">APPLE AIRPODS with details</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>20,000</span></b>
</div>
</div>
</div>
</div>
</div>
<div class="row">
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product4.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">New</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">APPLE IPOD with details</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>13,000</span></b>
</div>
</div>
</div>
</div>
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1 mt-small-5 mb-small-5">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product6.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">New</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">APPLE MAC BOOK with details</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>1,25,000</span></b>
</div>
</div>
</div>
</div>
<div class="col-md-4 col-12">
<div class="single_product shadow text-center p-1">
<div class="product_img">
<a href="product_detail.html"><img src="assets/images/product7.png"
class="img img-fluid" alt=""></a>
<div class="new_product">
<span class="badge py-2 px-3 badge-pill badge-danger">New</span>
</div>
</div>
<div class="product-caption my-3">
<div class="product-ratting">
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star"></i>
<i class="far fa-star low-star"></i>
<i class="far fa-star low-star"></i>
</div>
<h4><a href="product_detail.html">IPHONE 12 with details</a></h4>
<div class="price">
<b><span class="mr-1">₹</span><span>90,000</span></b>
</div>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- ==============products ends here============== -->






<!-- ==============feature starts here============== -->
<section class="feature py-5 mt-5" id="feature">
<div class="container">
<div class="section_title text-center mb-5">
<h1 class="text-capitalize">Our Features</h1>
</div>
<div class="row text-primary">
<div class="col-md-4 col-12 shadow p-3">
<div class="text-center">
<div class="mb-4">
<i class="fas fa-shipping-fast fa-3x mb-3 pt-2"></i>
<div>
<h3>Free Shipping Method</h3>
</div>
</div>
<div>
Products at Global business don’t have brand names or conspicuous logos. The website sells the stuff you need, like cleaning products, personal care, pantry items, and vitamins and supplements. All products have minimal packaging and are usually eco-friendly, with designations like nontoxic, organic, or fair trade. For example, tissues and toilet paper are made from bamboo, not trees.

If you favor minimalist design and have no brand loyalty, you can get free shipping through Brandless when they buy more than $48 worth of products. Fill your box with the products you regularly use, such as toilet paper and cleaning products, and set it to ship as often as you like — every two to eight weeks.
Global business also offers price matching online. If you find something on sale or at a lower price on another website, reach out to the Nordstrom customer service team and ask them to match the price. 
</div>
</div>
</div>
<div class="col-md-4 col-12 shadow p-3 mt-small-5 mb-small-5">
<div class="text-center">
<div class="mb-4">
<i class="fas fa-lock fa-3x mb-3 pt-2"></i>
<div>
<h3>Secure Payment System</h3>
</div>
</div>
<div>
Online business is a major part in the today’s business world. It is very easy way of purchasing and selling goods and services for the busy world. Payment gateways are integrated with online businesses. The general model for payment transaction is included five main parties. They are client, merchant, issuer which is the client’s financial institution, acquirer which is the merchant’s financial institution and the payment gateway. A payment gateway is a service that acts as an intermediary between the merchant’s web site, issuer and the acquirer. Customer is not directly interacts with the payment gateway
</div>
</div>
</div>
<div class="col-md-4 col-12 shadow p-3">
<div class="text-center">
<div class="mb-4">
<i class="fas fa-headphones fa-3x mb-3 pt-2"></i>
<div>
<h3>24/7 Support</h3>
</div>
</div>
<div>
Service and support play important roles in every company, and that’s especially true for those who sell directly to individual consumers. But as an e-commerce retailer, you can’t simply replicate the customer support approaches that your favorite traditional retailers use.

While some business owners make the mistake of viewing customer service as little more than the process of dealing with inevitable problems, it can play a much larger role in the company’s overall success. Excellent customer service can be a key differentiator that converts casual buyers into loyal customers. In fact, 59% of American consumers say that they’d try a new brand or company for a better service experience.
</div>
</div>
</div>
</div>
</div>
</section>
<!-- ==============feature ends here============== -->


<!-- ==============footer starts here============== -->
<section class="footer_section pt-5 pb-2" id="footer_section">
<footer>
<div class="container-fluid">
<div class="row">
<div class="col-md-3 col-6 pl-5 pl-small-15">
<div class="footer_title">
<a href="index.html"><img src="assets/images/logo.png" width="150px"
class="img img-fluid" alt="logo"></a>
</div>
<div>
Global business refers to international trade whereas a global business is a company doing business across the world. The exchange of goods over great distances goes back a very long time. 
</div>
</div>
<div class="col-md-3 col-6">
<div class="footer_title pt-3 mb-3">
<h3>Quick Links</h3>
</div>
<div class="footer_links">
<ul>
<li><a href="about.html">About</a></li>
<li><a href="javascript:;">Offers & Discounts</a></li>
<li><a href="javascript:;">Get Coupon</a></li>
<li><a href="contact.html">Contact Us</a></li>
</ul>
</div>
</div>
<div class="col-md-3 col-6">
<div class="footer_title pt-3 mb-3">
<h3>New Products</h3>
</div>
<div class="footer_links">
<ul>
<li><a href="javascript:;">Mobiles</a></li>
<li><a href="javascript:;">Headset</a></li>
<li><a href="javascript:;">Watches</a></li>
<li><a href="javascript:;">Airpods</a></li>
</ul>
</div>
</div>
<div class="col-md-3 col-6">
<div class="footer_title pt-3 mb-3">
<h3>Support</h3>
</div>
<div class="footer_links">
<ul>
<li><a href="javascript:;">Frequently Asked Questions</a></li>
<li><a href="javascript:;">Terms & Conditions</a></li>
<li><a href="javascript:;">Privacy Policy</a></li>
<li><a href="javascript:;">Report a Payment Issue</a></li>
</ul>
</div>
</div>
</div>
</div>
<div class="border-top">
<h6 class="text-center mt-3">Copyright ©2020 All rights reserved
</h6>
</div>
</footer>
</section>
<div class="backtop">
<a id="button" href="#top" class="btn btn-lg btn-outline-danger" role="button">
<i class="fas fa-chevron-up text-dark"></i>
</a>
</div>
<!-- ==============footer ends here============== -->


                      
<!-- Optional JavaScript -->
<!-- jQuery first, then Popper.js, then Bootstrap JS -->

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    <!-- Option 2: jQuery, Popper.js, and Bootstrap JS
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
    -->
  </body>
</html>
