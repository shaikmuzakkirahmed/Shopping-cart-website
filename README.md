# Shopping-cart-website
Source code of shopping cart website

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>One-Page Shopping Cart Website</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css" rel="stylesheet">
    <style>
        /* Custom CSS styles */
        /* Add your custom styles here */

        /* Navbar color and animation */
        .navbar {
            background-color: #6C5B7B; /* Purple color */
        }

        /* Product card animation */
        .product-card {
            animation: fadeInUp 0.5s ease forwards;
        }

        /* Carousel image height */
        .carousel-img {
            height: 300px;
            object-fit: cover;
        }
    </style>
</head>
<body>

<!-- Navigation Section -->
<nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
        <a class="navbar-brand" href="#">
            <img src="C:\Users\HP\iqra junior college\image\logo p1.png" alt="Logo" height="60"> <!-- Add your logo image and adjust the height as needed -->
            ShopperSpot</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="#">Your Orders</a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="#">Track Your Order</a>
                </li>
                <!-- Add additional navigation links as needed -->
            </ul>
            <form class="form-inline my-2 my-lg-0 mr-3">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-light my-2 my-sm-0" type="submit">Search</button>
            </form>
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Cart</a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="#">Login</a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="#">Sign Up</a>
                </li>
            </ul>
        </div>
    </div>
</nav>



<!-- Carousel Section -->
<section class="container my-4">
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img class="d-block w-100 carousel-img" src="C:\Users\HP\iqra junior college\image\big sale.png" alt="First slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100 carousel-img" src="C:\Users\HP\iqra junior college\image\big sale 1.png" alt="Second slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100 carousel-img" src="C:\Users\HP\iqra junior college\image\big sale 2.png" alt="Third slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100 carousel-img" src="C:\Users\HP\iqra junior college\image\cloth sale.png" alt="Fourth slide">
            </div>
            <div class="carousel-item">
                <img class="d-block w-100 carousel-img" src="C:\Users\HP\iqra junior college\image\sale.jpg" alt="Fifth slide">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>
</section>

<!-- Product Display Section -->
<section class="container my-5">
    <div class="row">
        <!-- Dummy product cards -->
        <div class="col-lg-4 col-md-6 mb-4 product-card animate__animated animate__fadeInUp">
            <div class="card h-100">
                <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\S23 Ultra.png" alt="Dummy Product 1">
                <div class="card-body">
                    <h4 class="card-title">Samsung S23 Ultra 256gb Storage 8gbRAM</h4>
                    <p class="card-text">Samsung S23 Ultra:

						200MP main camera, 8K video recording
						6.8-inch QHD+ AMOLED display, 120Hz refresh rate
						Snapdragon 8 Gen 2 processor, up to 16GB RAM
						5000mAh battery, 45W fast charging.</p>
                </div>
                <div class="card-footer">
                    <button class="btn btn-primary btn-block">Add to Cart</button>
                </div>
            </div>
        </div>
        <!-- Repeat this card structure for additional products -->
        <!-- Repeat this for 10 products -->
		<div class="col-lg-4 col-md-6 mb-4 product-card animate__animated animate__fadeInUp">
            <div class="card h-100">
                <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\iphone 15.png" alt="Dummy Product 2">
                <div class="card-body">
                    <h4 class="card-title">iphone 15pro max 256gb Storage 12gb RAM</h4>
                    <p class="card-text">iPhone 15 Pro Max:

						Triple rear camera system with improved low-light performance
						6.7-inch ProMotion OLED display, always-on display
						A17 Bionic chip, 5G connectivity
						Longer battery life, improved MagSafe wireless charging.</p>
                </div>
                <div class="card-footer">
                    <button class="btn btn-primary btn-block">Add to Cart</button>
                </div>
            </div>
        </div>

		<div class="col-lg-4 col-md-6 mb-4 product-card animate__animated animate__fadeInUp">
            <div class="card h-100">
                <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\OnePlus 12.png" alt="Dummy Product 3">
                <div class="card-body">
                    <h4 class="card-title">OnePlus 12 128gb Storage 12gb RAM</h4>
                    <p class="card-text">OnePlus 12
						RAM:	12GB / 16GB (LPDDR5X)
						Storage:	256GB / 512GB (UFS 4.0)
						OS (at launch)	OxygenOS 14 (atop Android 14)
						Primary camera:	50MP Sony LYT-T808 “Pixel Stacked” 1.12μm, ƒ/1.7, 1/1.43-inch sensor w/ OIS.</p>
                </div>
                <div class="card-footer">
                    <button class="btn btn-primary btn-block">Add to Cart</button>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Product Display Section -->
<section class="container my-5">
    <div class="row">
        <!-- Card 1 -->
        <div class="col-lg-6 mb-4 animate__animated animate__fadeInLeft">
            <div class="card shadow">
                <div class="card-body">
                    <h5 class="card-title">Starting ₹149 | Bestseling earbuds, headphones & more</h5>
                    <!-- Small Cards Inside -->
                    <div class="row">
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\noise.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Noise</p>
                                </div>
                            </div>
                        </div>
                        <!-- Repeat for Small Cards 2, 3, and 4 -->
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\Zeb.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Zebronics</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\Boat.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Boat</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\Boult.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Boult</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- "See All Offers" Button -->
                    <div class="text-center mt-4">
                        <a href="#" class="a-link-normal see-more truncate-1line">See All Offers</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- card -2 -->
        <div class="col-lg-6 mb-4 animate__animated animate__fadeInLeft">
            <div class="card shadow">
                <div class="card-body">
                    <h5 class="card-title">Up to 60% off | Styles for men</h5>
                    <!-- small cards Inside -->
                    <div class="row">
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\cloth.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Clothes</p>
                                </div>
                            </div>
                        </div>
                        <!-- Repeat for Small Cards 2, 3, and 4 -->
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\foot.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Footwear</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\watch.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Watches</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\bags.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Bags</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- "See All Offers" Button -->
                    <div class="text-center mt-4">
                        <a href="#" class="a-link-normal see-more truncate-1line">End of season sale</a>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- card-3 -->
        <div class="col-lg-6 mb-4 animate__animated animate__fadeInLeft">
            <div class="card shadow">
                <div class="card-body">
                    <h5 class="card-title">Starting ₹99 | All your home improvement needs</h5>
                    <!-- Small Cards Inside -->
                    <div class="row">
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\spin.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Spin mops, wipes & more</p>
                                </div>
                            </div>
                        </div>
                        <!-- Repeat for Small Cards 2, 3, and 4 -->
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\bath.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Bathroom hardware & accessories</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\hammer.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Hammers, Screwdrivers & more</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\extension.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Extension boards, plugs and more</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- "See All Offers" Button -->
                    <div class="text-center mt-4">
                        <a href="#" class="a-link-normal see-more truncate-1line">Explore all</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- card-4 -->
        <div class="col-lg-6 mb-4 animate__animated animate__fadeInLeft">
            <div class="card shadow">
                <div class="card-body">
                    <h5 class="card-title">Up to 60% off | Styles for women</h5>
                    <!-- Small Cards Inside -->
                    <div class="row">
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\women.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Women's Clothing</p>
                                </div>
                            </div>
                        </div>
                        <!-- Repeat for Small Cards 2, 3, and 4 -->
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\footw.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Footwear+Handbags</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\Watches.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Watches</p>
                                </div>
                            </div>
                        </div>
                        <div class="col-6 mb-3">
                            <div class="card small-card shadow">
                                <div class="card-body">
                                    <img class="card-img-top" src="C:\Users\HP\iqra junior college\image\fashion.jpg" alt="Dummy Product 1">
                                    <h6 class="card-title"></h6>
                                    <p class="card-text">Fashion jewellery</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- "See All Offers" Button -->
                    <div class="text-center mt-4">
                        <a href="#" class="a-link-normal see-more truncate-1line">Explore all</a>
                    </div>
                </div>
            </div>
        </div>

<!-- Shopping Cart Display -->
<section class="bg-light py-5">
    <div class="container">
        <h2 class="text-center mb-4">Shopping Cart</h2>
        <!-- Dummy cart items -->
        <div class="row">
            <div class="col-md-8">
                <ul class="list-group">
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        Product 1
                        <span class="badge badge-primary badge-pill">1</span>
                    </li>
                    <!-- Repeat this list item structure for each cart item -->
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        Product 2
                        <span class="badge badge-primary badge-pill">1</span>
                    </li>
                    <!-- Repeat this list item structure for each cart item -->
                    <li class="list-group-item d-flex justify-content-between align-items-center">
                        Product 3
                        <span class="badge badge-primary badge-pill">1</span>
                    </li>
                    <!-- Repeat this list item structure for each cart item -->
                </ul>
            </div>
            <div class="col-md-8">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Total</h5>
                        <p class="card-text">Total Price: $1500</p>
                        <a href="#" class="btn btn-primary btn-block">Checkout</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>



<!-- Bootstrap JS and jQuery -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
