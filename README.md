# OIBSIP_1
This is landing page
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Teko&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style type="text/css">
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        header{
            width: 100%;
            height: 100vh;
            background:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)),url("Background.jpg");
            background-size: cover;
        }
        nav{
            width: 100%;
            height: 100px;
            background-size: cover;
            color: rgb(165, 24, 42);
            display: flex;
            justify-content: space-around;
            align-items: center;
            font-family: sans-serif;
        }
        .logo{
            font-size: 2em;
            letter-spacing: 2px;

        }
        .Menu a{
            text-decoration: none;
            color: rgb(21, 23, 26);
            padding: 10px 20px;
            font-size: 20px;
            position: relative;
        }
        .Menu a:before{
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 0%;
            height: 100%;
            border-bottom: 2px solid rgb(11, 16, 25);
            transition: 0.4s linear;
        }

        .Menu a:hover:before{
            width: 90%;
        }
        
        .Register a{
            text-decoration: none;
            color: rgb(255, 255, 255);
            padding: 10px 20px;
            font-size: 20px;
            background: rgb(255, 98, 0);
            border-radius: 5px;
            transition: 0.4s linear;
        }

        .Register a:hover{
            background: black;
            border: 1px solid rgb(148, 48, 48);
        }
        .h-txt{
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            text-align: center;
            color: rgb(118, 52, 52);
        }
        .h-txt span{
            letter-spacing: 5px;
        }
        
        .h-txt h1{
            font-size: 3.5em;
        }
        
        .h-txt a{
            text-decoration: none;
            background: rgb(255, 165, 0);
            color: rgb(188, 56, 56);
            padding: 15px,25px;
            letter-spacing: 5px;
            transition: 0.4s linear;
        }
        .h-txt a:hover{
        background: black;
            border: 1px solid rgb(34, 0, 255);
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <b>Explore world</b>
            </div>
            <div class="Menu">
                <a href="#"><b>Home</b></a>
                <a href="#"><b>Hill Stations</b></a>
                <a href="#"><b>Best Offer's</b></a>
                <a href="#"><b>Contact Us</b></a>
            </div>
            <div class="Register">
                <a href="#">Register</a>
            </div>
        </nav>
        <section class="h-txt">
            <span><b>Enjoy</b></span>
            <h1><b>GO TRAVEL</b></h1>
            <br>
            <a href="#"><b>Book Your Trip Now</b></a>
        </section>
</header>   
</body>
</html
