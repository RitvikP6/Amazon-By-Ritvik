<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon-like Website</title>
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <style>
        .navbar-brand img {
            max-height: 40px;
        }

        .navbar-nav .nav-link {
            color: #ffffff !important;
            margin-right: 15px;
        }

        .form-inline input[type="search"] {
            width: 300px;
        }

        .card {
            margin-bottom: 20px;
        }

        .footer {
            background-color: #232f3e;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .nav-item {
            display: flex;
            align-items: center;
        }

        .nav-item svg {
            margin-left: 0px;
            /* Adjust this value as needed */
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="https://www.amazon.in/">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a9/Amazon_logo.svg" width="30" height="30"
                class="d-inline-block align-top" alt="">
            Amazon.in
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="https://www.amazon.in/">All</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"
                        href="https://www.amazon.in/alm/storefront?almBrandId=ctnow&ref_=nav_cs_fresh">Fresh</a>
                </li>
                <li class="nav-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="white" class="bi bi-controller"
                        viewBox="0 0 16 16">
                        <path
                            d="M11.5 6.027a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0m-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0m-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1m-6.5-3h1v1h1v1h-1v1h-1v-1h-1v-1h1z" />
                        <path
                            d="M3.051 3.26a.5.5 0 0 1 .354-.613l1.932-.518a.5.5 0 0 1 .62.39c.655-.079 1.35-.117 2.043-.117.72 0 1.443.041 2.12.126a.5.5 0 0 1 .622-.399l1.932.518a.5.5 0 0 1 .306.729q.211.136.373.297c.408.408.78 1.05 1.095 1.772.32.733.599 1.591.805 2.466s.34 1.78.364 2.606c.024.816-.059 1.602-.328 2.21a1.42 1.42 0 0 1-1.445.83c-.636-.067-1.115-.394-1.513-.773-.245-.232-.496-.526-.739-.808-.126-.148-.25-.292-.368-.423-.728-.804-1.597-1.527-3.224-1.527s-2.496.723-3.224 1.527c-.119.131-.242.275-.368.423-.243.282-.494.575-.739.808-.398.38-.877.706-1.513.773a1.42 1.42 0 0 1-1.445-.83c-.27-.608-.352-1.395-.329-2.21.024-.826.16-1.73.365-2.606.206-.875.486-1.733.805-2.466.315-.722.687-1.364 1.094-1.772a2.3 2.3 0 0 1 .433-.335l-.028-.079zm2.036.412c-.877.185-1.469.443-1.733.708-.276.276-.587.783-.885 1.465a14 14 0 0 0-.748 2.295 12.4 12.4 0 0 0-.339 2.406c-.022.755.062 1.368.243 1.776a.42.42 0 0 0 .426.24c.327-.034.61-.199.929-.502.212-.202.4-.423.615-.674.133-.156.276-.323.44-.504C4.861 9.969 5.978 9.027 8 9.027s3.139.942 3.965 1.855c.164.181.307.348.44.504.214.251.403.472.615.674.318.303.601.468.929.503a.42.42 0 0 0 .426-.241c.18-.408.265-1.02.243-1.776a12.4 12.4 0 0 0-.339-2.406 14 14 0 0 0-.748-2.295c-.298-.682-.61-1.19-.885-1.465-.264-.265-.856-.523-1.733-.708-.85-.179-1.877-.27-2.913-.27s-2.063.091-2.913.27" />
                    </svg>
                    <a class="nav-link"
                        href="https://www.amazon.in/video-games/b/?ie=UTF8&node=976460031&ref_=nav_cs_video_games">Video
                        Games</a>
                </li>
                <li class="nav-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="white" class="bi bi-tv"
                        viewBox="0 0 16 16">
                        <path
                            d="M2.5 13.5A.5.5 0 0 1 3 13h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5M13.991 3l.024.001a1.5 1.5 0 0 1 .538.143.76.76 0 0 1 .302.254c.067.1.145.277.145.602v5.991l-.001.024a1.5 1.5 0 0 1-.143.538.76.76 0 0 1-.254.302c-.1.067-.277.145-.602.145H2.009l-.024-.001a1.5 1.5 0 0 1-.538-.143.76.76 0 0 1-.302-.254C1.078 10.502 1 10.325 1 10V4.009l.001-.024a1.5 1.5 0 0 1 .143-.538.76.76 0 0 1 .254-.302C1.498 3.078 1.675 3 2 3zM14 2H2C0 2 0 4 0 4v6c0 2 2 2 2 2h12c2 0 2-2 2-2V4c0-2-2-2-2-2" />
                    </svg>
                    <a class="nav-link" href="https://www.amazon.in/minitv?ref_=nav_avod_desktop_topnav">Amazon
                        miniTV</a>
                </li>
                <li class="nav-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="White" class="bi bi-wallet"
                        viewBox="0 0 16 16">
                        <path
                            d="M3.5 4a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 .5.5v.5h-10v-.5zM2 5h12a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm0-1C1 4 0 5 0 6v8c0 1 1 2 2 2h12c1 0 2-1 2-2V6c0-1-1-2-2-2H2zm0 1h12v8H2V6zm4 4.5a.5.5 0 0 1 .5-.5.5.5 0 0 1 0 1 .5.5 0 0 1-.5-.5z" />
                    </svg>
                    <a class="nav-link"
                        href="https://www.amazon.in/b/32702023031?node=32702023031&ld=AZINSOANavDesktop_T3&ref_=nav_cs_sell_T3">Sell</a>
                </li>
                <li class="nav-item">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="white" class="bi bi-gift-fill"
                        viewBox="0 0 16 16">
                        <path
                            d="M3 2.5a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0v.006c0 .07 0 .27-.038.494H15a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h2.038A3 3 0 0 1 3 2.506zm1.068.5H7v-.5a1.5 1.5 0 1 0-3 0c0 .085.002.274.045.43zM9 3h2.932l.023-.07c.043-.156.045-.345.045-.43a1.5 1.5 0 0 0-3 0zm6 4v7.5a1.5 1.5 0 0 1-1.5 1.5H9V7zM2.5 16A1.5 1.5 0 0 1 1 14.5V7h6v9z" />
                    </svg>
                    <a class="nav-link"
                        href="https://www.amazon.in/gift-card-store/b/?ie=UTF8&node=3704982031&ref_=nav_cs_gc">Gift
                        Cards</a>
                </li>
                <li class="nav-item">
                    <img src="download.png" width="45" height="55" class="d-inline-block align-top" alt="">
                </li>
            </ul>
            <form class="form-inline my-2 my-lg-0">
                <form class="form-inline my-2 my-lg-0">
                    <input class="form-control mr-sm-2" type="search" placeholder="Search Amazon.in"
                        aria-label="Search">
                    <a href="#" class="btn btn-primary"
                        onclick="window.location.href='https://www.amazon.in/'">Search</a>

                    <a class="nav-link" href="https://www.amazon.com/gp/css/homepage.html/181-1307215-8299047">Hello,
                        User</a>
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="white"
                        class="bi bi-person-square" viewBox="0 0 16 16">
                        <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0" />
                        <path
                            d="M2 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2zm12 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1v-1c0-1-1-4-6-4s-6 3-6 4v1a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1z" />
                    </svg>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link"
                            href="https://www.amazon.in/gp/css/order-history?ref_=nav_orders_first">Returns & Orders</a>
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="white"
                            class="bi bi-bag-check" viewBox="0 0 16 16">
                            <path fill-rule="evenodd"
                                d="M10.854 8.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 0 1 .708-.708L7.5 10.793l2.646-2.647a.5.5 0 0 1 .708 0" />
                            <path
                                d="M8 1a2.5 2.5 0 0 1 2.5 2.5V4h-5v-.5A2.5 2.5 0 0 1 8 1m3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4zM2 5h12v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1z" />
                        </svg>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.amazon.in/gp/cart/view.html?ref_=nav_cart">Cart</a>
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="white" class="bi bi-cart"
                            viewBox="0 0 16 16">
                            <path
                                d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M3.102 4l1.313 7h8.17l1.313-7zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2" />
                        </svg>
                    </li>
                    </ul>
        </div>
    </nav>
    <!-- Product Cards -->
    <div class="container mt-4">
        <div class="row" id="product-row">
            <!-- Page 1 Cards -->
            <div class="col-md-4 col-sm-6 mb-4">
                <div class="card h-100">
                    <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9" class="card-img-top"
                        alt="Smartphone X200">
                    <div class="card-body">
                        <h5 class="card-title">Galaxy S23</h5>
                        <p class="card-text">Latest model with high-resolution camera.</p>
                        <p> Price: <b>$797.96</b></p>
                        <a href="#" class="btn btn-primary"
                            onclick="window.location.href='https://www.amazon.in/SAMSUNG-Galaxy-S23-Mint-Storage/dp/B0CJHX5L5V/ref=sr_1_4_mod_primary_new?adgrpid=1316117036976099&dib=eyJ2IjoiMSJ9.3FMtT2xKArbJpTPXqGYqM-3imQ-NkGlBk0s3deoc0GjFCJYWfxgl7neqNctU-gPiRYhjDYX4j_MeXt3A4Bnomj9PEwxjUshGmKoZYDthwNRO5_gnSbFuJzX67jdeUCcpDp_WBh8VswwQFwkWKnZ2oOhb9ub_XfBQdVBnnljTbEls6nBeoMBq87my-cNMrfOm8-7DH6h-HMyhzCsxsusMQkUH-dppHRc4I2i5BqmBUL0.VXVfRhhM_Fl8GjCikczQLVZAcMLSAIxB3pkhv544yi0&dib_tag=se&hvadid=82257585702397&hvbmt=be&hvdev=c&hvlocphy=149155&hvnetw=o&hvqmt=e&hvtargid=kwd-82258212623577%3Aloc-90&hydadcr=26417_2800897&keywords=s23+fe&qid=1723432175&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sr=8-4'">View
                            Details</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4 col-sm-6 mb-4">
                <div class="card h-100">
                    <img src="https://images-na.ssl-images-amazon.com/images/G/02/aplusautomation/vendorimages/245d4476-7fc2-433f-8c22-abccc03569f4.jpg._CB485976157_.jpg"
                        alt="Wireless Headphones">
                    <div class="card-body">
                        <h5 class="card-title">Wireless Headphones</h5>
                        <p class="card-text">Noise-cancelling over-ear headphones.</p>
                        <p> Price: <b>$292.56</b></p>
                        <a href="#" class="btn btn-primary"
                            onclick="window.location.href='https://www.amazon.in/Sennheiser-Momentum-Wireless-Headphones-Designed/dp/B0CCRZPKR1/ref=sr_1_2_sspa?crid=C1MZT91G58FA&dib=eyJ2IjoiMSJ9.A2kPY0OJcqjQ9N5sMB05VMPRrkCE1WvTnHEIv0-FPV3Z7ra5YsA8579wzeciSom-BT7KoZjUNCjuDAopux409ZRL_rJBIuSsN0wYaj7J832bWnBBKQ25OU_joI4uvQ7LJJ3ZuW7O1Eieeb8Fgb7MGj2GwlBmxAidWVi6FhqtYu07gjUazMzBrhqomUHBz9tlKawZUBP-8P_eG9qlyxXYRwIGk54bgxg-m2l3uBA8xLE.k6FgAHdUrSc3a_6CdfBUsAJTn9DMAyugqaezuSTRTvs&dib_tag=se&keywords=sony+headphones&qid=1723432401&sprefix=sony+head%2Caps%2C225&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1'">View
                            Details</a>
                    </div>
                </div>
            </div>
            <!-- Repeat for additional cards... -->
            <!-- Data for cards -->
            <script>
                const productData = [
                    {
                        "image": "https://th.bing.com/th/id/OIP.lCK40Qe1NGEsFhcj7eBjpgAAAA?rs=1&pid=ImgDetMain",
                        "title": "Gaming Laptop",
                        "description": "Powerful gaming laptop with a high refresh rate display.",
                        "cost": "₹61,990",
                        "buyNowUrl": "https://www.amazon.in/Samsung-Processor-Windows-Fingerprint-Graphics/dp/B0D143SJ9R/ref=sr_1_3?crid=2MW2BCEFSG2W5&dib=eyJ2IjoiMSJ9.avH4cIJyXIgswfxu9-Kdk0KcybFYlZFApJfanpYtU3eHWtpJOmTDyU8QXWnNApMF3r8u1__YYYk5I69-CxoZ17WOlleU5IKkhTJMow_MQ7BPlTzLlD8rWsO_D42T5dD5WXI8B-yAwyGNCDqhx3YkduVGXurtrXU6rCbpMr04Lq7DIiLfW6dJFYDkoWKrKirKoZ41xlwSSOsZxt-WyXmfBgLVrXAZRFEZARVn4LWgpqQkjsHBrZgq9whEzznBBdfLkdsveb_ODIbMJ_LLNYVtawrh61mLdOVBi4MzHFsQPZw.af66iYFKJRq7j15Rd99U1rxHTjDM6RbL7nXn6aLDmec&dib_tag=se&keywords=gaming+laptop+samsung&qid=1723364570&s=computers&sprefix=gaming+laptop+samsung%2Ccomputers%2C245&sr=1-3"
                    },
                    {
                        "image": "https://www.bamdeal.com/wp-content/uploads/2020/11/android-smart-watch-iphone-compatible-smartwatch-for-women-men-fitness.jpg",
                        "title": "Smartwatch",
                        "description": "Fitness tracker with heart rate monitoring and GPS.",
                        "cost": "₹1199",
                        "buyNowUrl": "https://www.amazon.in/Noise-Launched-Bluetooth-Calling-Tracking/dp/B0BJ72WZQ7/ref=sr_1_4?crid=38D0BO4NY84ZP&dib=eyJ2IjoiMSJ9.NtkgNnxdfq3wRW-lf8_5O6p51D5hVorg0oAsOdRQgAZn3Xq0DR_1eRnfN5QsIMN09uLPEYfEOB7m0lTiM4mtwZ0YdeI9fCeo4zu9W2BOWgjpnxfql7pjPbBiAiEkqMJ198bY78fUnw1eIVnYX2gILkJlf8M6yaKywKV9ZBIj7pYkef3Vcw8DkF8n-MmiAFBsM2kTcj3yRWVhIWfRIeLqmCYgbjx3SMhr9r2S_semGPS7doRLB19QRBbgSUCMObewuL5O5EGduLVmxIsYtPKzzszqfZsUm3JgwFEHTWHFp8A.nj7DUU1K5mlJp81xR4N-WH4-aacLZt7n1n5TWhwfTA8&dib_tag=se&keywords=watch&qid=1723366090&s=computers&sprefix=watch%2Ccomputers%2C281&sr=1-4"
                    },
                    {
                        "image": "https://i5.walmartimages.com/asr/cdaaab64-5ea7-4d8f-969f-cff666244723.ff62693361b001ebbaf41145d23c0f13.jpeg",
                        "title": "Wireless Speaker",
                        "description": "Portable Bluetooth speaker with excellent sound quality.",
                        "cost": "₹979",
                        "buyNowUrl": "https://www.amazon.in/boAt-Stone-Bluetooth-Speaker-Black/dp/B08JMC1988/ref=sr_1_3?crid=2TZQD5EGS37LB&dib=eyJ2IjoiMSJ9.Bq1RDDDqqZsogJFyU27J2RPwFR0kracUCPBQovMXesMgCiU7KV1HOH44S81Sy8xiYDDvchpD-_sL47rTJXInpMK7vBGr695Z9OgsdrMAeURUUni9ddYAoJmOGaHndAQDSjMWLw6a3g12DDdbPny2SKGW1t4FS7uof_NzUnOzw4ElcuHWNbFSj9THz-Ec3rODko8t9f1o5wmwKd-G-HZShusu6f5Dl_ecKYTQj1ZP5PT6ua8dfI15pYks1X8YjrkmxZA3mpmrUn20GBiNrZbU3bvhJOZ37SMN_KfRR9z6buc.rzDua7SWQzoGs-xZNddIuUDHrpWDY_9lrn-q60FWA_4&dib_tag=se&keywords=small+speaker&qid=1723366117&s=computers&sprefix=small+speaker%2Ccomputers%2C224&sr=1-3"
                    },
                    {
                        "image": "https://th.bing.com/th/id/R.6c28092016f6fb0e96edf4574faca96d?rik=XR9zhA0iw7%2ffjw&riu=http%3a%2f%2fwww.bhphotovideo.com%2fimages%2fimages2000x2000%2fsony_ilce_5000b_k_alpha_a5000_mirrorless_digital_1022331.jpg&ehk=11kKG3EUGXgwKcrI9B0kYv3FKN4E39oMO920IVj6iyA%3d&risl=&pid=ImgRaw&r=0",
                        "title": "Camera",
                        "description": "High-resolution camera with a wide-angle lens.",
                        "cost": "₹80,000",
                        "buyNowUrl": "https://www.amazon.in/Sony-ILCE-6100Y-Mirrorless-Real-time-Tracking/dp/B081JRLB4P/ref=sr_1_4_mod_primary_new?crid=1SDX2SNLTHXR0&dib=eyJ2IjoiMSJ9.td4S4kqGF9VIn8l8dW4hXjPONMr4LZ3Lt7uCrGZM3GGG6UlF-Z9MuKbVqzhq1WD5Hq1yNG-_S3FEbniUGImT6l_JrAvA4VmtFekG3oFZtvKYh_Q1WAP_s7mNGoWtnUS_PIEZ2f3W3q5z6fq68Nd3eDkFQYTRTIc7Eyy-6gbZdKL974OZdB9So0oDkCxoBl6sbwekEQy1TTcEWbq83MTD8Te2kBTIKINvV0QjH13OEqvM9mMVZFIUIHz4HyZiTzlfYznugKCMablDOZPTSCzrcaJyMCMgtjn89sW_DYqbHWQ.SQgByDZDYFokd4Hp7OVJrgiuyQH6kcMxj2-e5M_HUWg&dib_tag=se&keywords=CAMERA+SONY&qid=1723366345&s=computers&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=camera+sony%2Ccomputers%2C232&sr=1-4"
                    },
                    {
                        "image": "https://cdn.comparez-malin.fr/img/samsung/2023/34565/samsung-galaxy-tab-s9-11-anthracite-1.jpg",
                        "title": "Tablet",
                        "description": "Lightweight and versatile tablet for entertainment and work.",
                        "cost": "₹90,478",
                        "buyNowUrl": "https://www.amazon.in/Samsung-Galaxy-Dynamic-Display-Expandable/dp/B0CCRTZSFJ/ref=sr_1_1_sspa?crid=2OFALS1JVADAW&dib=eyJ2IjoiMSJ9.Wi0jCS3ePpNscdPFu2huJn-ffa5thSZ-LBWOmwYE7wP54d-nHbNcdKTfaun3pYVZopD2GHdIpR6mTu3dypzPDdLHw79EkFsVKClbAZrWbC-qfIhGWYfGs03UpVezdyl-px84sODZM74Rzevu7Cp-FDA9EIi0_68x0c-45OzKlcXLMAAttG1fieu43MxlQO9ZqTIE7tP5RdSsthMcyiboVLkXqoJKSzFemIa0Z-EvnO4OidogRKitSqCz61QN558eB7_njU3HqPrafPpLLF2CTdx_xzynir6n2Igik0Z2W0c.IxtVMw7yg9ryAOv3mSVoWdswe84gXe47wktkEv3DfYo&dib_tag=se&keywords=tab+samsung&qid=1723366422&s=computers&sprefix=TAB+%2Ccomputers%2C238&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"
                    },
                    {
                        "image": "https://2.bp.blogspot.com/-d5Lgv3VwGM0/VqZdN4x0TuI/AAAAAAAAiAs/IaO95f-Yors/s1600/home-theater-systems-design-l-7d77fa04c7a73bb8.jpg",
                        "title": "Home Theater System",
                        "description": "Immersive home theater experience with surround sound.",
                        "cost": "₹5009",
                        "buyNowUrl": "https://www.amazon.in/GOVO-GOSURROUND-subwoofer-Satellites-Bluetooth/dp/B0CF9NVXW5/ref=sr_1_1_sspa?crid=PBADLRGCMYC6&dib=eyJ2IjoiMSJ9.sjddq2IdmwEiPlNibs-IYUnptijyRLHiHIJrI6EEhqJVNt8P2sidLK1sRCq_7Zk1kq4QSs4AHAogFDjjN3I9-lSWygOVXst0QjENS--9M8RX7Xpu9kuaU9QbEBnyNUdVPvJgiEHage9qgnm2pX3NxhRdhswJWQM7bL5Pb8dG-nOuIRZtsfhHzU6xkDMrZSwsuMQs5JhsLcrdxP8b9VXeZxKeeoRoT6zbF9svyR1NSVIM6divdaxN389QSGeG6M8lrZmkDb-gVFEnveywJxsaQVEzJyNc8vNYwTGAcugZDV8.wcNNxC2Cao9_NlpvWDSbl3qT6CtKHKjJ_aQ5tHbZRVk&dib_tag=se&keywords=HOME+THEATER&qid=1723366462&s=computers&sprefix=home+theater%2Ccomputers%2C238&sr=1-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"
                    },
                    {
                        "image": "https://th.bing.com/th/id/OIP.VDAOZuKqt2ilrKdEfw_7YAHaHa?rs=1&pid=ImgDetMain",
                        "title": "Air Purifier",
                        "description": "Clean and fresh air for a healthier home.",
                        "cost": "₹15,789",
                        "buyNowUrl": "https://www.amazon.in/MI-Purifier-Efficiency-Airpollutants-Control-Alexa/dp/B0C1P65Y4H/ref=sr_1_4?dib=eyJ2IjoiMSJ9.bDOE-wKrWaSdNUtPeBYLotHHUasFl9CEp-J6TM4GOqRNlltSrcVZl4wNm9IKNW54xhXgComyMo0PvJSwqMHG1IkobDhFUT6MgaKAfq6jTxRIceVCAIwzXdZuk42vaNtWDtIqySfOpNEoP28kRY7NXDWLgol3BtJvg7mXBOVT0fi3wUo2k4N5krk--4xo9vTVSphAL_wMEFy4haDBKq41cxwPr0sd8lhcUJDB2ANH-X8.qjhqGvxn26sUGGVOtrKfANVXom648i3TUR2nPuJk8hc&dib_tag=se&keywords=AIR+PURIFIER&qid=1723366513&sr=8-4"
                    },
                    {
                        "image": "https://images-na.ssl-images-amazon.com/images/I/71Sujy-eqKL._SL1500_.jpg",
                        "title": "Robot Vacuum Cleaner",
                        "description": "Automated vacuum cleaner for a spotless home.",
                        "cost": "₹29,589",
                        "buyNowUrl": "https://www.amazon.in/Dreame-Self-Emptying-Advanced-Navigation-Compatible/dp/B0BKGLJJT4/ref=sr_1_2_sspa?crid=OA1W9EZE2CBX&dib=eyJ2IjoiMSJ9.faiUSCTMu3jaaGeVf3-0sN1ohRHfWs_vTDcVO14e3e7eFQ9Sn4yhN4EdcEES2giq8HJrjlfOUCi0OOFKX7UOKpzsN7sefoo_kMYxvpRGc-hDeoiLVIFyTH6c-cc78NjmzkM3MewfmPzqHkSnnrapD3gTF_s0raQCNFfxs7qhjZ2y3XMyj9c5tL6unlk6Y3ohj5WSSDViKErW2yYtohmYKn896ZMmKHhJjj7Vx1UeA1c.cuYvhYypNme7y4Q4J7opxrciLORHDAoyfSlgcko2Ok4&dib_tag=se&keywords=robot+vacuum+cleaner&qid=1723366566&sprefix=ROBOT+%2Caps%2C253&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"
                    },
                    {
                        "image": "https://www.cartoq.com/wp-content/uploads/2021/12/OLA-S1-Pro_2.jpg",
                        "title": "Electric Scooter",
                        "description": "Eco-friendly and convenient way to commute.",
                        "cost": "₹50,649",
                        "buyNowUrl": "https://www.amazon.in/AMO-Electric-Scooter-Jaunty-Battery/dp/B0D9RW56NL/ref=sr_1_9?crid=DOG5N6X47AQT&dib=eyJ2IjoiMSJ9.kzz1_ANF19cEwOLkUUtUmAfmnAslPC2WxT91UQlQuP_u1QZo5qdU9JX_EzcEWT-7_N5jMbII5olFFN4oLci3Jc7xsuDOdMCQyrYBkHTyLfWNGOcMxXZBm_W02fpFRdUlsJGoA00MIR7WDcZFYJPC4wIxH8tM4rwA2nKNUfkNqkKCI_QrHiW_T4jB_Spcnj3q1VP9x04utsLb3t94VTWKPKeJB-6tXsiM3msaZKjXZigz1YSOEL0C5ultqBtwIcSIBs73l8ie1vrHFSNYJWKhNwGrDgTFCnbIewrwER498O8.Ed4JeANMIPFyRtgb3z5WdecB-Djx8gZgwwOj3CmZ7dc&dib_tag=se&keywords=electric%2Bscooter&qid=1723366623&sprefix=electic%2Bscooter%2Caps%2C257&sr=8-9&th=1"
                    },
                    {
                        "image": "https://th.bing.com/th/id/OIP.Qe7TbgAxJ6k7rOdjtGcPPwHaEK?rs=1&pid=ImgDetMain",
                        "title": "Drones",
                        "description": "Capture stunning aerial footage.",
                        "cost": "₹2,999",
                        "buyNowUrl": "https://www.amazon.in/Foldable-Altitude-Headless-Positioning-Multicolor/dp/B0DC6RNMVS/ref=sr_1_21_sspa?crid=WMYZQCQLST82&dib=eyJ2IjoiMSJ9.nSmXSJDFOljl3aa-Tp1hTskEzVfwMDgwn5D1hk0Ov1k9z7TYXSKfaSjM_Dp4-zrP_HJaZ10Es5ed9ARa31cv-3iq4G5QH7SgmnlRKzc1ZTho93ZmAG_v6PWu3CrNHuRizN1Os1FDuajlrUq8UcZfCqwTEUxs_bseVjWa1h1Om8HsP6LqHRT2MT__yVPH-kVR9If0mAr_J5GhxyO9W0ozhmnQxcUVeotOu5pyNv8DP7vyMVWqeNaiVTtJKnrwchTH-KS6kIOmWxe-7KPpMsfctepbdaNYeJSzTmKtyaCJ0NQ.qULR61NBIWBBXxochkkcq_RrdHBexLk10yUTlqXA-Mo&dib_tag=se&keywords=DJI+DRONE&qid=1723366674&sprefix=dji+drone%2Caps%2C249&sr=8-21-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1"
                    },
                    {
                        "image": "https://cdn.abcotvs.com/dip/images/14296939_apple-vision-pro-getty-img.jpg",
                        "title": "Virtual Reality Headset",
                        "description": "Immersive virtual reality experience.",
                        "cost": "₹25,689",
                        "buyNowUrl": "https://www.amazon.in/Oculus%C3%82-Advanced-Virtual-Reality-Headset/dp/B099VMT8VZ/ref=sr_1_4?crid=3K6763QXRAQ4I&dib=eyJ2IjoiMSJ9.kOUPJwE737EICw3EsH-eV-eUQQNFQr4S4ByAtYxQpKL98WVQEhv-sINl4F_uCyhV0NkXVxEsfF7rjKIuDJIvYUBhIfnZVdJC4lnzYnSH_NAWqDyYjGjKNDHGVRVlCXUFBkpIiS3rQK9PfI1qTmLgAGNR2l7E1yfEGUYHRvNxAXEVMslpY5h10N02jfpnP_h5TGE4U5uNTH_DHJ2ZchReknij_qvITunCK1I4laLnD_k.sD2srTKYnUggQHKVUB7LmbZPPVgqkv-U4OukJt8eqdE&dib_tag=se&keywords=apple+vision+pro&qid=1723366777&sprefix=APPLE+V%2Caps%2C249&sr=8-4"
                    },
                    {
                        "image": "https://cdn.thewirecutter.com/wp-content/media/2021/03/fitness-tracker-2048px-garmin-app.jpg?auto=webp&quality=75&width=980&dpr=2",
                        "title": "Fitness Tracker",
                        "description": "Track your fitness goals and stay motivated.",
                        "cost": "₹2,569",
                        "buyNowUrl": "https://www.amazon.in/MI-Personal-Activity-Intelligence-Tracking/dp/B08GXC2NTX/ref=sr_1_4?crid=36FLJB7IE1QK6&dib=eyJ2IjoiMSJ9.5_onJIt6v2PjJiWlkt9BtNwYB8KuVvyvOttfuCIjP0e_jQpCJZujcFZStEZBtkKkz-k6JeC5DhiDx34HWcoJpk-1FTLEPG1neXz_SCxsFgZGNf16i569TbMAJhTgydydu8EtDDLlkw-CS_c08GW74huGnFv3wL_QUXVRfHG2uoT8_Kfp1ssmbqZkyiCrWPmDdUKj-nSr0hW4kCcuv_xGquxmOy5eqvWD6BnO7oAQqNA.rbS54MLmVlBwjn0ST9dRb3Y3bGSUz-dBSWCTBzqkimM&dib_tag=se&keywords=fitness+tracker&qid=1723366828&sprefix=FITNESS+%2Caps%2C257&sr=8-4"
                    },
                ];
            </script>
            <script>
                productData.forEach(product => {
                    const cardHTML = `
                        <div class="col-md-4 col-sm-6 mb-4">
                            <div class="card h-100">
                                <img src="${product.image}" class="card-img-top" alt="${product.title}">
                                <div class="card-body">
                                    <h5 class="card-title">${product.title}</h5>
                                    <p class="card-text">${product.description}</p>
                                    <p class="card-text">Price: <b>${product.cost}</b></p> 
                                    <a href="${product.buyNowUrl}" class="btn btn-primary">Buy Now</a> 
                                </div>
                            </div>
                        </div>
                    `;
                    document.querySelector('.row').innerHTML += cardHTML;
                });
            </script>
            <!-- Pagination -->
            <nav aria-label="Page navigation example">
                <ul class="pagination justify-content-center">
                    <li class="page-item disabled">
                        <a class="page-link" href="#" tabindex="-1" aria-disabled="true">Previous</a>
                    </li>
                    <li class="page-item"><a class="page-link" href="index.html">1</a></li>
                    <li class="page-item"><a class="page-link" href="https://www.amazon.in/">Amazon</a></li>

                    </li>
                </ul>
            </nav>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer bg-dark text-light pt-4">
        <div class="container">
            <div class="row">
                <!-- Customer Service -->
                <div class="col-md-3">
                    <h5>Customer Service</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://www.amazon.in/gp/help/customer/display.html?nodeId=G508510&ref_=footer_gw_m_b_he"
                                class="text-light">Help</a></li>
                        <li><a href="https://www.amazon.in/gp/css/returns/homepage.html?ref_=footer_hy_f_4"
                                class="text-light">Returns</a></li>
                        <li><a href="https://shipping.amazon.in/" class="text-light">Shipping</a></li>
                        <li><a href="https://www.amazon.in/gp/help/customer/display.html%3FnodeId%3DGENAFPTNLHV7ZACW"
                                class="text-light">Track Your Order</a></li>
                    </ul>
                </div>

                <!-- About Amazon -->
                <div class="col-md-3">
                    <h5>About Amazon</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://www.amazon.jobs/en/teams/in" class="text-light">Careers</a></li>
                        <li><a href="https://www.amazon.in/b?node=1592137031" class="text-light">Press Releases</a></li>
                        <li><a href="https://www.amazon.in/gift-card-store/b/?ie=UTF8&node=3704982031&ref_=nav_cs_gc"
                                class="text-light">Gift Cards</a></li>
                    </ul>
                </div>

                <!-- Make Money with Us -->
                <div class="col-md-3">
                    <h5>Make Money with Us</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://sell.amazon.in/" class="text-light">Sell on Amazon</a></li>
                        <li><a href="https://affiliate-program.amazon.in/?utm_campaign=assocshowcase&utm_medium=footer&utm_source=GW&ref_=footer_assoc"
                                class="text-light">Affiliate Program</a></li>
                        <li><a href="https://advertising.amazon.com/en-gb?ref=Amz.in&initialSessionID=262-8060525-8191020&ld=NSBing"
                                class="text-light">Advertise Your Products</a></li>
                        <li><a href="https://kdp.amazon.com/en_US/" class="text-light">Self-Publish with Us</a></li>
                    </ul>
                </div>

                <!-- Payment Methods -->
                <div class="col-md-3">
                    <h5>Payment Methods</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://www.amazon.in/gp/help/customer/display.html%3FnodeId%3DGFBWMNXEPYVJAY9A#:~:text=Following%20Credit%20and%20Debit%20cards%20can%20be%20used,and%20Maestro%20All%20international%20cards%20can%20be%20used"
                                class="text-light">Credit & Debit Cards</a></li>
                        <li><a href="https://www.amazon.in/gift-card-store/b/?ie=UTF8&node=3704982031&ref_=nav_cs_gc"
                                class="text-light">Gift Cards</a></li>
                        <li><a href="https://www.amazon.in/amazonpay/home" class="text-light">Amazon Pay</a></li>
                    </ul>
                </div>
            </div>



            <div class="row mt-3">
                <div class="col-md-12 text-center">
                    <p>&copy; 2024 Amazon All rights reserved.</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/AmazonIN" class="text-light mx-2">Facebook</a>
                        <a href="https://x.com/AmazonIN" class="text-light mx-2">Twitter</a>
                        <a href="https://www.instagram.com/amazondotin/" class="text-light mx-2">Instagram</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>


</body>

</html>
