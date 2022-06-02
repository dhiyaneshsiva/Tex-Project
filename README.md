# Tex-Project
Source Code 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ambara Export | Home</title>
    <!-- Bootstrap Link -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <!-- font awesome kit  -->
    <script src="https://kit.fontawesome.com/607329fa87.js" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/607329fa87.js" crossorigin="anonymous"></script>
    <!-- Google fonts link -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Orelega+One&display=swap" rel="stylesheet">

    <!-- custom Styles -->
    <style>
        :root {
            --background-color: #f3c175e3;
            /* Background Color Root */
            --text-color: #2E3192;
            /*text Color */
            --main-content-bcg: #F6F6F6;
        }

        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        img {
            width: 100%;
            height: 100%;
        }

        /* Common Class For Some needed Element  */
        .width-height {
            width: 100%;
            height: 100%;
        }

        .header1 {
            width: 100%;
            height: 8vh;
            background-color: var(--background-color);
            border-bottom: 2px dashed black;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
        }

        .header-list {
            display: flex;
            justify-content: flex-start;
            /* background-color: var(--text-color); Used Just To Check */
            height: 8vh;
            width: 60%;
        }

        .header-list li {
            align-items: center;
            list-style-type: none;
            margin: 10px;

        }

        .header-list li a {
            text-decoration: none;
            color: rgb(0, 0, 0);
        }

        .bi-envelope {
            /* color: red; */
            background-color: black;
        }

        .header-logo {
            justify-content: space-between;
            /* background-color: var(--text-color); used To Check*/
            height: 8vh;
            width: 15%;
            justify-content: space-between;
        }

        .insta-logo {
            /* background-color: var(--text-color); used to check*/
            width: 500px;
            height: 500px;
            font-size: 30px;
            text-align: center;
        }

        .twitterologo {
            margin-left: 30px;
        }

        .fa-instagram {
            color: white;
            font-size: 25px;
            text-align: center;
        }

        .fa-linkedin {
            color: white;
            font-size: 25px;
            text-align: center;
        }

        @media only screen and (max-width:730px) {
            .phone-number {
                /* display: none; */
                font-size: 70%;
            }

            .email-id {
                font-size: 70%;
            }

        }

        @media only screen and (max-width:600px) {

            /* body {
                display: none;
            } */
            .phone-number {
                /* display: none; */
                text-align: center;
                width: 100%;
                position: relative;
                margin: auto;
            }

            .header1 {
                height: 17vh;
                width: 100%;
            }

            .header1-main {
                margin: auto;
                /* height: 20vh; */
                width: 80%;
                /* background-color: black; */
                display: block;
            }

            .header-list {
                width: 100%;
                /* background-color: palevioletred; */
                margin: auto;
            }

            .header-list li {
                margin: auto;
            }

            .email-id {
                text-align: center;
                width: 100%;
                position: relative;
                margin: auto;
            }

            .header-logo {
                /* display: none; */
                margin-top: 50px;
                display: flex;
                position: absolute;
                margin-left: 33%;
            }

            .insta-logo {
                margin-top: -12px;
            }

            .twitterologo {
                margin-left: 40%;
            }
        }

        @media only screen and (max-width:500px) {
            .header1 {
                height: 10vh;
            }

            .header2-logo {
                width: 100%;
            }
        }

        @media only screen and (max-width:360px) {
            .email-id {
                font-size: 60%;
                position: relative;
            }

            .phone-number {
                font-size: 60%;
            }

            .fa-linkedin {
                font-size: 90%;
                position: absolute;
                margin-top: -1px;
            }

            .fa-instagram {
                font-size: 50%;
                position: absolute;
                margin-top: 10px;
            }

            .header1 {
                height: 12vh;
            }

            .header2-logo img {
                width: 30%;
            }
        }

        @media only screen and (max-width:350px) {
            .email-id {
                font-size: 50%;
            }

            .phone-number {
                font-size: 50%;
            }

            .header1 {
                height: 8vh;
            }

            .header2-logo img {
                width: 50%;
            }
        }

        @media only screen and (max-width:280px) {
            .email-id {
                font-size: 40%;
                margin: auto;
            }

            .phone-number {
                font-size: 40%;
                margin: auto;
            }

            .fa-linkedin {
                font-size: 54%;
                position: absolute;
                margin-top: -1px;
            }

            .fa-instagram {
                font-size: 30%;
                position: absolute;
                margin-top: 10px;
            }

            .header1 {
                height: 6vh;
            }

            .header2-logo img {
                width: 30%;
            }
        }

        li {
            list-style-type: none;
        }

        a {
            text-decoration: none;
            color: rgba(0, 0, 0, 0.342);
            font-size: 15px;
        }

        .header2 {
            margin-top: 2px;
            /* background-color: red; */
            height: 15vh;
            border-bottom: 2px solid var(--text-color);
            position: relative;
        }

        .header2-container {
            width: 100%;
            margin: auto;
            display: flex;
            justify-content: space-between;
        }

        .header2-logo {
            height: 14vh;
            display: flex;
            width: 50%;
        }

        .header2-logo img {
            border-radius: 50%;
            width: 20%;
            margin-left: 5%;
        }

        .h1 {
            /* margin: auto; */
            margin-top: auto;
            margin-bottom: auto;
            margin-left: 10px;
        }

        .nav-links {
            display: flex;
            width: 50%;
            justify-content: space-evenly;
            margin: auto;
        }

        .nav-links li .black {
            color: black;
        }

        .fa-bars {
            font-size: 30px;
            display: none;
            margin: auto;
        }

        @media only screen and (max-width:800px) {
            .nav-links {
                /* display: none; */
                flex-direction: column;
                position: absolute;
                background-color: #2E3192;
                width: 0%;
                text-align: center;
                top: 100%;
                left: -32px;
                transition: all 300ms;
            }

            a {
                color: rgba(255, 255, 255, 0.404);
            }

            .nav-links li .black {
                color: white;
            }

            .nav-links li a:hover {
                color: white;
            }

            .fa-bars {
                /* font-size: 30px; */
                display: block;
                margin-right: 5%;
            }

            .h1 {
                margin: auto;
                text-align: center;
            }

            .header2-logo {
                justify-content: space-between;
                width: 80%;
            }
        }

        .nav-show {
            width: 100%;
            z-index: 1;
            right: 0px;
            left: 0px;
        }

        @media only screen and (max-width:800px) {
            .h1 {
                font-size: 80%;
                text-align: center;
                margin-top: auto;
                margin-bottom: auto;
                margin-left: 10%;
            }

            .header2 {
                height: 9vh;
            }

            .fa-bars {
                font-size: 80%;
            }

            .header2-logo {
                height: 8vh;
                width: 40%;
            }
        }

        .image1 {
            position: relative;
            height: 100vh;
        }

        @media only screen and (max-width:700px) {
            .image1 {
                position: relative;
                height: 70vh;
            }
        }

        .welcome1 {
            text-align: center;
        }

        .blue {
            color: var(--text-color);
        }

        #welcome-para {
            text-align: center;
            margin-left: auto;
            width: 50%;
            margin-top: 10px;
            margin-bottom: 40px;
            margin-right: auto;
            font-size: 20px;
            padding: 5px;
            color: var(--main-content-bcg);
            background-color: var(--text-color);
        }

        @media only screen and (max-width:500px) {
            .image1 {
                height: 40vh;
            }

            #welcome-para {
                width: 100%;
                font-size: auto;
            }
        }

        main {
            width: 100%;
            background-color: var(--main-content-bcg);
            height: 100%;
        }

        .main-content {
            width: 85%;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            height: 100%;
        }

        .main-content .process {
            color: var(--text-color);
            text-align: center;
        }

        .main-content .process-para {
            text-align: center !important;
        }

        .factory {
            display: flex;
            /* background-color: red; */
            height: 22vh;
        }

        .factory-main {
            margin-left: 7%;
        }

        .factory h1 {
            color: var(--text-color);
        }

        .factory-image {
            width: 10%;
            height: 15vh;
            margin-top: auto;
            margin-bottom: auto;
        }

        .Design-Studio {
            display: flex;
            /* background-color: red; */
            height: 18vh;
            margin-top: 2%;
        }

        .Design-Studio-main {
            margin-left: 7%;
        }

        .Design-Studio h1 {
            color: var(--text-color);
        }

        .Design-Studio-image {
            width: 10%;
            height: 15vh;
            margin-top: auto;
            margin-bottom: auto;
        }

        /* .Design-Studio-para {
            display: none;
        } */
        .Selection-of-yarn {
            display: flex;
            /* background-color: red; */
            height: 25vh;
            margin-top: 2%;
        }

        .Selection-of-yarn-main {
            margin-left: 7%;
        }

        .Selection-of-yarn-h1 {
            color: var(--text-color);
        }

        .Selection-of-yarn-image {
            width: 10%;
            height: 15vh;
            margin-top: auto;
            margin-bottom: auto;
        }

        .Checking {
            display: flex;
            /* background-color: red; */
            height: 25vh;
            margin-top: 2%;
        }

        .Checking-main {
            margin-left: 7%;
        }

        .Checking-h1 {
            color: var(--text-color);
        }

        .Checking-image {
            width: 10%;
            height: 15vh;
            margin-top: auto;
            margin-bottom: auto;
        }

        .Packaging {
            display: flex;
            /* background-color: red; */
            height: 25vh;
            margin-top: 2%;
        }

        .Packaging-main {
            margin-left: 7%;
        }

        .Packaging-h1 {
            color: var(--text-color);
        }

        .Packaging-image {
            width: 10%;
            height: 15vh;
            margin-top: auto;
            margin-bottom: auto;
        }

        @media only screen and (max-width:1040px) {
            .Checking {
                display: flex;
                /* background-color: red; */
                height: 25vh;
                margin-top: 6%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 100%;
                margin-top: 4%;
            }
        }

        @media only screen and (max-width:890px) {

            .Design-Studio,
            .Selection-of-yarn {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 6%;
            }

            .Checking {
                display: flex;
                /* background-color: red; */
                height: 28vh;
                margin-top: 12%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 100%;
                margin-top: 2%;
            }
        }

        @media only screen and (max-width:890px) {
            .Design-Studio {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 10%;
            }

            .Checking {
                display: flex;
                /* background-color: red; */
                height: 28vh;
                margin-top: 16%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 100%;
                margin-top: 4%;
            }
        }

        @media only screen and (max-width:710px) {
            .Checking {
                display: flex;
                /* background-color: red; */
                height: 28vh;
                margin-top: 22%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 100%;
                margin-top: 8%;
            }

            .Design-Studio,
            .Selection-of-yarn {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 10%;
            }

            footer {
                background-color: var(--text-color);
                width: 100%;
                height: 100%;
                display: flex;
                flex-direction: column;
                margin: auto;
            }

            .location {
                margin: auto;
            }

            .location h1 {
                color: white;
                margin: auto;
                text-align: center;
            }

            .contact {
                margin: auto;
            }

            .contact h1 {
                color: white;
                text-align: center;
            }
        }

        @media only screen and (max-width:600px) {
            .Checking {
                display: flex;
                /* background-color: red; */
                height: 28vh;
                margin-top: 32%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 100%;
                margin-top: 16%;
            }

            .Design-Studio {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 18%;
            }

            .Selection-of-yarn {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 14%;
            }
        }

        @media only screen and (max-width:536px) {
            .Checking {
                display: flex;
                /* background-color: red; */
                height: 28vh;
                margin-top: 42%;
            }

            .Packaging {
                display: flex;
                /* background-color: red; */
                height: 45vh;
                margin-top: 22%;
            }

            .Design-Studio {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 22%;
            }

            .Selection-of-yarn {
                display: flex;
                /* background-color: red; */
                height: 18vh;
                margin-top: 14%;

            }

            .factory-para,
            .Design-Studio-para,
            .Selection-of-yarn-para,
            .Checking-para,
            .Packaging-para {
                text-align: justify
            }
        }

        @media only screen and (max-width:500px) {

            .factory-para,
            .Checking-para,
            .Selection-of-yarn-para,
            .Packaging-para,
            .Design-Studio-para {
                margin-left: auto;
                margin-right: auto;
            }

            .main-content {
                margin: auto;
            }

            .factory {
                display: block;
                height: 100%;
                margin: auto;
                text-align: center;
                align-items: center;
            }

            .Checking {
                display: block;
                height: 100%;
                /* background-color: red; */
                margin: auto;
                text-align: center;
                align-items: center;
            }

            .Selection-of-yarn {
                display: block;
                height: 100%;
                margin: auto;
                text-align: center;
                align-items: center;
            }

            .Packaging {
                display: block;
                height: 100%;
                margin: auto;
                text-align: center;
                align-items: center;
            }

            .Design-Studio {
                display: block;
                height: 100%;
                margin: auto;
                text-align: center;
                align-items: center;
                /* background-color: red; */
            }

            footer {
                background-color: var(--text-color);
                width: 100%;
                height: 100%;
                margin-top: -16px;
            }

            .location {
                width: 100%;
                height: 100%;
                margin: auto;
            }

            .location-para {
                width: 100%;
                height: 100%;
            }

            .contact {
                height: 100%;
            }
        }

        @media only screen and (max-width:500px) {

            .factory img,
            .Design-Studio img,
            .Selection-of-yarn img,
            .Checking img,
            .Packaging img {
                width: 13%;
                height: 13%;
            }

        }

        footer {
            background-color: var(--text-color);
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: space-evenly;
        }

        .contact {
            color: white;
            margin-top: 2%;
        }

        .location {
            margin-top: 1%;
        }

        .location-para {
            height: 30vh;
        }

        .location h1 {
            color: white;
        }

        .experience {
            background-color: var(--background-color);
            width: 100%;
            margin-top: 1%;
        }

        .exp-list li h1 {
            text-align: center;
            font-weight: bolder;
            margin-top: 2%;
            color: white;
        }

        .exp-list li p {
            font-weight: 400;
            font-size: 25px;
            color: white;
        }

        .exp-list {
            display: flex;
            padding: 20px;
            justify-content: space-evenly;
        }

        .fa-star,
        .fa-fedora,
        .fa-500px,
        .fa-people-group {
            font-size: 50px;
            padding-top: 5px;
        }

        .year-exp,
        .clients,
        .production,
        .worker {
            text-align: center;
        }

        @media only screen and (max-width:1000px) {
            .exp-list li h1 {
                text-align: center;
                padding: 2%;
                margin-top: 2%;
            }

            .exp-list li p {
                font-size: auto;
                text-align: center;
            }

            .exp-list {
                display: flex;
                flex-direction: column;
                padding: 40px;
                justify-content: space-evenly;
            }
        }

        .us {
            width: 100%;
            margin-top: 2%;
            margin-bottom: 2%;
        }

        .y-us {
            color: var(--text-color);
        }

        .us h1,
        p {
            color: black;
            text-align: center;
        }

        .us-content {
            height: 100%;
            width: 100%;
        }

        .us-content-list {
            display: flex;
        }

        .us-content-list li {
            text-align: center;
        }

        .us-content-list li img {
            width: 20%;
            height: 40%;
        }

        .us-content-list li h1 {
            font-size: 20px;
            text-align: center;
            color: var(--text-color);
        }

        @media only screen and (max-width:850px) {
            .us-content-list {
                display: flex;
                flex-direction: column;
            }

            .us-content-list li img {
                width: 10%;
                height: 10%;
            }
        }

        @media only screen and (max-width:500px) {
            .us-content-list img {
                width: 12%;
                height: 12%;
            }
        }

        .our-products {
            margin: auto;
            width: 100%;
            background-color: var(--main-content-bcg);
            padding: 20px;
        }

        .our-products h1 {
            text-align: center;
        }

        .product-color {
            color: var(--text-color);
        }

        .pic-list {
            display: flex;
        }

        .pic-list li img {
            padding: 10px;
        }

        .pic-list li h1 {
            font-size: 20px;
        }

        .pic-list2 {
            display: flex;
            margin-top: 5%;
        }

        .pic-list2 li img {
            padding: 10px;

        }

        .pic-list2 li h1 {
            font-size: 20px;
        }

        .pic-list2 li {
            margin-bottom: 4%;
        }

        @media only screen and (max-width:640px) {
            .pic-list {
                display: flex;
                flex-direction: column;
            }

            .pic-list2 {
                display: flex;
                flex-direction: column;
            }

            .pic-list li {
                text-align: center;
            }

            .pic-list2 li {
                text-align: center;
            }

            .pic-list li img {
                width: 50%;
                height: 50%;
            }

            .pic-list li h1 {
                font-size: 70%;
            }

            .pic-list2 li h1 {
                font-size: 70%;
            }

            .pic-list2 li img {
                height: 50%;
                width: 50%;

            }
        }
    </style>
</head>

<body>
    <header class="header1">
        <div class="header1-main">
            <div class="header-content">
                <ul class="header-list">
                    <li><a href="#" class="email-id"> <i
                                class="fa-solid fa-envelope"></i>&nbsp;dhiyanesh.siva@outlook.com </a></li>
                    <!-- Instgram ID  -->
                    <li><a href="#" class="phone-number"> <i class="fa-solid fa-phone"></i>&nbsp;+91 8428466822 </a>
                    </li> <!-- Contact Number  -->
                </ul>
                <div class="header-logo">
                    <span class="insta-logo"><i class="fa-brands fa-instagram"></i></span> &nbsp;
                    <span class="twitterologo"><i class="fa-brands fa-linkedin"></i></span>
                </div>
            </div>
        </div>
    </header>
    <header class="header2">
        <div class="header2-container">
            <div class="header2-logo">
                <img src="data:image/png;base64,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"
                    alt="logo">

                <h1 class="h1"> AMBARA EXPORT </h1>
            </div>
            <ul class="nav-links">
                <li><a href="#" class="black">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="#">Quality</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Process</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
            <i class="fa-solid fa-bars"></i>
        </div>
    </header>
    <div class="image-slide">
        <img src="https://atlas.in/files/2020/01/slider3-min.jpg" class="image1" alt="">
    </div>
    <div class="experience">
        <ul class="exp-list">
            <li class="year-exp">
                <i class="fa-regular fa-star"></i><i class="fa-regular fa-star"></i><i class="fa-regular fa-star"></i>
                <h1>20+</h1>
                <p>YEARS OF EXPERIENCE</p>
            </li>
            <li class="worker">
                <i class="fa-solid fa-people-group"></i>
                <h1> 500+</h1>
                <p>DEDICATED WORKERS</p>
            </li>
            <li class="production">
                <i class="fa-brands fa-fedora"></i>
                <h1> 500+</h1>
                <p>PRODUCTS</p>
            </li>
            <li class="clients">
                <i class="fa-brands fa-500px"></i>
                <h1> 800+</h1>
                <p>SATISFIED CLIENTS</p>
            </li>
        </ul>
    </div>
    <main>

        <div class="main-content">
            <h1 class="welcome1">
                Welcome to <span class="blue"> AMBARA EXPORT</span>
            </h1>
            <div id="welcome-para">
                Manufacturer and Exporter of Home Textile Made-Ups
            </div>

            <h1 class="process">
                Process
            </h1>
            <p class="process-para">We have team of workforce who are closely monitoring with high AQL standards right
                from sampling to shipment with a proactive approach enabling to prevent potential problems and ensure
                timely delivery of the finished goods. We have total faith in our diligent and disciplined team of
                professional experts who are helping us to supply outstanding products with proper time management.</p>
            <div class="factory">
                <img src="https://www.ambalhometex.com/assets/img/icon/010.png" class="factory-image" alt="">
                <div class="factory-main">
                    <h1 class="factory-h1">Factory</h1>
                    <p class="factory-para">Ambara Export is a 35,000 square feet of manufacturing unit located at
                        Karur, TamilNadu. It houses our state-of-the-art production line, as well an in-house design
                        studio. Our factory is also built with Wal-mart Standards. We create a friendly and a beautiful
                        ambience for our employees.</p>
                </div>
            </div>
            <div class="Design-Studio">
                <img src="https://www.ambalhometex.com/assets/img/icon/011.png " class="Design-Studio-image" alt="">
                <div class="Design-Studio-main">
                    <h1 class="Design-Studio-h1">Design Studio</h1>
                    <p class="Design-Studio-para">Beside our local designers, we also have a team of overseas designers
                        to explore new designs and to create unique patterns. We occasionally hire freelance designers
                        to meet customer needs.</p>
                </div>
            </div>
            <div class="Selection-of-yarn">
                <img src="https://www.ambalhometex.com/assets/img/icon/011.png " class="Selection-of-yarn-image" alt="">
                <div class="Selection-of-yarn-main">
                    <h1 class="Selection-of-yarn-h1">Selection of yarn</h1>
                    <p class="Selection-of-yarn-para">We use 100% pure cotton and when needed 100% organic cotton yarn
                        to make our products feel as good as they look. We also use custom materials like viscose,
                        linen, polyester, flux, chenille, fancy yarns etc., upon request to suit your needs. We believe
                        that the product is only as good as the raw material, and so we procure our yarn only from
                        certified standard mills which ensures it is free from nips and knots.</p>
                </div>
            </div>
            <div class="Checking">
                <img src="https://www.ambalhometex.com/assets/img/icon/015.png" class="Checking-image" alt="">
                <div class="Checking-main">
                    <h1 class="Checking-h1">Checking</h1>
                    <p class="Checking-para">We at Ambara Export consider quality as our identity. We work hard in
                        bringing out the bets qualitied articles to our customers. We check the product at every stage
                        to avoid mistakes. Corrections are done using air pressure methods and with rubbers. We also
                        check the fabric quality, colours and prints at our labs to bring out perfection.</p>
                </div>
            </div>
            <div class="Packaging">
                <img src="https://www.ambalhometex.com/assets/img/icon/016.png" class="Packaging-image" alt="">
                <div class="Packaging-main">
                    <h1 class="Packaging-h1">Packaging</h1>
                    <p class="Packaging-para">Customer satisfaction is our utmost importance. Our products are
                        meticulously stuffed and packed by our experienced and enthusiastic workforce. We ship out our
                        deliveries on time, taking the destination and statutory requirements into account. We use the
                        Tuticorin Port Trust for exports and also Mumbai port, kochi port if requested. We also do
                        e-sealing in-house.</p>
                </div>
            </div>
        </div>
    </main>
    <div class="us">
        <h1>Why <span class="y-us">Choose Us</span></h1>
        <p>We are highly confident in our promise to give you better. Our focus is to build long term relationships with
            our customers, not simply a quick sale!

        </p>
    </div>
    <div class="us-content">
        <ul class="us-content-list">
            <li>
                <img src="https://www.ambalhometex.com/assets/img/icon/004.png" alt="">
                <h1>On-time Delivery</h1>
                <p>Our products & services to the buyers through time delivery & enhancing customers satisfaction</p>
            </li>
            <li>
                <img src="https://www.ambalhometex.com/assets/img/icon/001.png" alt="">
                <h1>Satisfied Customers</h1>
                <p>Since the inception of our firm, we are focused on maintaining the trust and enhancing Customers
                    Satisfaction.</p>
            </li>
            <li>
                <img src="https://www.ambalhometex.com/assets/img/icon/002.png" alt="">
                <h1>Competitive Price</h1>
                <p>Our company’s biggest agenda is to give a competitive price against our competitors.</p>
            </li>
            <li>
                <img src="https://www.ambalhometex.com/assets/img/icon/003.png" alt="">
                <h1>Product Quality</h1>
                <p>All our organized and sustained efforts are driven towards providing the customers.</p>
            </li>
        </ul>
    </div>
    <div class="our-products">
        <h1> Our <span class="product-color">Products</span></h1>
        <p>Ambara Export uses 100% pure cotton and when needed 100% organic cotton yarn to make our products feel as
            good as they look.</p>
        <div class="product-pic">
            <ul class="pic-list">
                <li>
                    <img src="https://www.ambalhometex.com/assets/img/product/kitchen/apron2.jpg" alt="">
                    <h1>KITCHEN LINEN</h1>
                </li>
                <li>
                    <img src="https://www.ambalhometex.com/assets/img/product/table/tablecloth.jpg" alt="">
                    <h1>TABLE LINEN</h1>
                </li>
                <li> <img src="https://www.ambalhometex.com/assets/img/product/bed/quilts1.jpg" alt="">
                    <h1>BED LINEN</h1>
                </li>
                <li> <img src="https://www.ambalhometex.com/assets/img/product/cushion/floor1.jpg" alt="">
                    <h1>CUSHIONS</h1>
                </li>
            </ul>
            <ul class="pic-list2">
                <li><img src="https://www.ambalhometex.com/assets/img/product/toy/toy.jpg" alt="">
                    <h1>TOYS</h1>
                </li>
                <li><img src="https://www.ambalhometex.com/assets/img/product/baby/sleeping1.jpg" alt="">
                    <h1>BABY TEXTILES</h1>
                </li>
                <li><img src="https://www.ambalhometex.com/assets/img/product/accessories/tea-cozy1.jpg" alt="">
                    <h1>ACCESSORIES</h1>
                </li>
                <li><img src="https://www.ambalhometex.com/assets/img/product/curtain/window.jpg" alt="">
                    <h1>CURTAINS</h1>
                </li>
            </ul>
        </div>
    </div>
    <footer>
        <div class="contact">
            <h1 class="footer-header">CONTACT</h1>
            <p class="address">
                <i class="fa fa-location-arrow"></i>
                AMBARA EXPORT <br>
                &nbsp;&nbsp;&nbsp;&nbsp;Vennamalai post, <br>
                &nbsp;&nbsp;&nbsp;&nbsp;Karur- 639006, Tamilnadu
            </p>
            <p class="number">
                <i class="fa fa-phone" aria-hidden="true"> </i>
                +91 84284 66822
            </p>
            <p class="mail-id">
                <i class="fa fa-envelope" aria-hidden="true"></i>
                dhiyanesh.siva@outlook.com
            </p>
        </div>
        <div class="location">
            <h1 class="location">
                LOCATE US
            </h1>
            <p><iframe class="location-para"
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7833.616031158437!2d78.07885932158229!3d10.977859101279497!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3baa2e4dac61fb6d%3A0xac37cb637bebe850!2sVengamedu%2C%20Tamil%20Nadu%20639006!5e0!3m2!1sen!2sin!4v1651161815759!5m2!1sen!2sin"
                    width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"></iframe></p>
        </div>
    </footer>
    <script>
        let dhiya = document.querySelector(".fa-bars");
        let Links = document.querySelector(".nav-links");

        dhiya.addEventListener('click', () => {
            Links.classList.toggle("nav-show");
        });
    </script>
</body>

</html>
