<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome !!</title>

    <!-- css CDN link -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">

    <!-- js CDN link -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <style>
        body {
            background-color: #000;
            color: #fff;
        }

        ::-webkit-input-placeholder {
            color: #fff !important;
        }

        .nav-item {
            opacity: 85%;
            transition: transform 0.5s;
        }

        .nav-item:hover {
            text-decoration: overline;
            color: #FFBD08;
            opacity: 100%;
            transform: scale(1.2);
        }

        .underl1 {
            opacity: 100%;
            border: solid 1px #FFBD08;
            color: #fff;
            width: 90%;
            margin: 0 35% 0 5%;
        }

        .intro {
            text-align: center;
        }

        .u3 {
            font-size: 4rem;
            color: #FFBD08;
        }

        .vid {
            text-align: center;
        }

        .join1 {
            width: 300px;
            height: 40px;
            color: #fff;
            font-size: 1.5rem;
            border: none;
            border-radius: 20px;
            background-color: #DE0B0A;
        }

        .join1:hover {
            color: #000;
            font-size: 1.5rem;
            border: none;
            border-radius: 20px;
            background-color: #fff;
        }

        .underl2 {
            opacity: 100%;
            border: solid 1px #FFBD08;
            color: #fff;
            width: 70%;
            margin: 0 35% 0 15%;
        }

        .underl3 {
            opacity: 100%;
            border: solid 1px #FFBD08;
            color: #fff;
            width: 50%;
            margin: 0 65% 0 25%;
        }

        .skl-img {
            text-align: center;
            width: 1150px;
            margin-left: 7%;
        }

        .me-5 {
            margin-bottom: 60px;
            border: solid 2px #FFBD08;
            border-radius: 10px;
            transition: transform 0.5s;
        }

        .me-5:hover {
            transform: scale(1.2);
        }

        .underl4 {
            opacity: 100%;
            border: solid 1px #FFBD08;
            color: #fff;
            width: 20%;
            margin: 0 40% 0 15%;
        }
    </style>
</head>
<body>
    <div class="container bg-dark sticky-top">
        <div class="navbar nav-expand-lg">
            <!-- logo -->
            <div class="navbar-brand">
                <span href="#" class="text-light fs-1">UNO</span>
            </div>

            <!-- nav-items -->
            <ul class="navbar nav">
                <li class="nav-item">
                    <a href="#" class="nav-link me-2 text-light fs-5">Home</a>
                </li>
                <li class="nav-item">
                    <a href="#skills" class="nav-link me-2 text-light fs-5">Courses</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link me-2 text-light fs-5">FAQ's</a>
                </li>
                <li class="nav-item">
                    <a href="#" class="nav-link me-2 text-light fs-5">Login</a>
                </li>
            </ul>

            <!-- Search bar -->
            <div class="d-flex">
                <input type="text" class="form-control bg-transparent me-4" placeholder="Search ....">
                <button class="btn btn-outline-light">Search</button>
            </div>
        </div>
    </div>
    <hr class="underl1">
    <br><br>
    <div class="intro">
        <h1 class="u1">Welcome to</h1>
        <h1 class="u3">UNO</h1>
        <h5 style="margin-left: 300px;">By <span style="color: #FFBD08;">Varun</span></h5>
    </div>
    <br>
    <div class="vid">
        <iframe src="https://player.vimeo.com/video/878052023?h=61906ad230" width="940" height="560" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
        <br><br>
        <button class="join1">JOIN NOW</button>
        <br><br>
        <p style="font-size: 1.2rem;"><span style="background-color: #DE0B0A;">220,978+</span> students have already taken  advantage of this opportunity.</p>
    </div>
    <br><br>

    <!-- What is UNO ? -->
    <h2 style="font-size: 4rem; text-align: center;">What is UNO 1.0 ?</h2>
    <hr class="underl2">
    <br><br>
    <div class="what-is" style="margin-left: 135px;">
        <img style="float: left;" src="/andrewh.png" alt="Sorry, we will fix it soon ...">
        <div>
            <p style="font-size: 1.6rem; width: 530px; margin-left: 475px;"><b>UNO 1.0</b> is a sponsored website of <b>Hustlers University</b>, also known as <b>The Real World</b>. This is an exclusive community where you will have private access to:</p>
            <ul style="font-size: 1.4rem; width: 530px; margin-left: 530px;">
                <li>E-commerce</li>
                <li>Dropshipping</li>   
                <li>Stocks/options</li>
                <li>Crypto/NFT's</li>
                <li>Investing</li>
                <li>Marketing</li>
                <li>Business</li>
                <li>Fitness/Nutrition</li>
                <li>Artificial intelligence</li>
                <li id="skills">Social media mastery</li>
                <li>and much more ...</li>
            </ul>
        </div>
    </div>
    <br><br>

    <!-- Skills -->
    <h2 style="font-size: 4rem; text-align: center;">What Skills will i learn ?</h2>
    <br>
    <hr class="underl3">
    <br><br><br><br>
    <div class="skl-img">
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-01.png" alt="sorry, we will fix it soon ...">
            <h5>Business Mastery</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-02.png" alt="sorry, we will fix it soon ...">
            <h5>Copywriting</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-03.png" alt="sorry, we will fix it soon ...">
            <h5>Content Creation</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-04.png" alt="sorry, we will fix it soon ...">
            <h5>E-commrece</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-05.png" alt="sorry, we will fix it soon ...">
            <h5>Freelancing</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-06.png" alt="sorry, we will fix it soon ...">
            <h5>Crypto</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-07.png" alt="sorry, we will fix it soon ...">
            <h5>Ai</h5>
        </div>
        <div style="display: inline-block; width: 170px; padding: 20px 0 20px 0" class="me-5">
            <img src="./hu-08.png" alt="sorry, we will fix it soon ...">
            <h5>Stocks/options</h5>
        </div>
    </div>
    <br><br>

    <!-- info -->
    <div style="width: 900px; margin-left: 15%;">
        <img src="./hu-ad-1.png" style="float: right; margin-top: 120px;" alt="Sorry, we will fix it soon ...">
        <h2 style="font-size: 3.5rem;">Make Money Online from Anywhere</h2>
        <br>
        <hr class="underl4">
        <br><br>
        <p style="font-size: 1.4rem;"><b>True freedom</b> is being able to do whatever you want, wherever you want, whenever you want in the real world.</p>
        <br>
        <p style="font-size: 1.4rem;">Everything taught at Hustler's University allows you to make money online, which means you can be anywhere in the real world making money.</p>
        <br>
        <p style="font-size: 1.4rem;">Whether you are at home, at the beach, or on vacation, as long as you have an internet connection you can make money.</p>
    </div>

    <div style="width: 900px; margin-left: 15%;">
        <img src="./tate-1.png" style="float: left; margin-top: 220px;" alt="Sorry, we will fix it soon ...">
        <h2 style="font-size: 3.5rem; text-align: left;">Multiply your earnings</h2>
        <br>
        <hr class="underl4">
        <br><br>
        <p style="font-size: 1.4rem;"><b>True freedom</b> is being able to do whatever you want, wherever you want, whenever you want in the real world.</p>
        <br>
        <p style="font-size: 1.4rem;">Everything taught at Hustler's University allows you to make money online, which means you can be anywhere in the real world making money.</p>
        <br>
        <p style="font-size: 1.4rem;">Whether you are at home, at the beach, or on vacation, as long as you have an internet connection you can make money.</p>
    </div>
</body>
</html>
