<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha512-9usAa10IRO0HhonpyAIVpjrylPvoDwiPUiKdWk5t3PyolY1cOd4DSE0Ga+ri4AuTroPR5aQvXU9xC6qOPnzFeg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>

        *{
            padding: 0px;
            margin: 0px;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }
        .header_app{
            background-color: green;
            padding-left: 12px;
            height: 41px;
        }
        #header_logo{
            text-decoration: none;
            color: white;
            font-size: 19px;
            font-family: Arial, Helvetica, sans-serif;
            font-weight: bold;

        }
        .main_nav{
            display: inline-block;
            width: calc(100% - 99px);
            text-align: right;
        }
        .main_nav_lists{
            text-align: right;
            padding-top: 12px;
            padding-right: 12px;
        }
        #main_nav_list{
            list-style-type: none;
            display: inline-block;
        }
        #main_nav_list a{
            color: white;
            text-decoration: none;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 15px;
            margin-right: 10px;
        }
        #how_ıt_works{
            width: auto;
            height: auto;
            padding: 34px;
            background-color: wheat;
            text-align: center;
            color: #3e4555;
        }
        #nova{
            width: auto;
            height: 500px;
            padding: 34px;
            background-color: wheat;
            
        }
        #main_nav_list_login{
            color: white;
            background-color: #2E4C6D;
            border-radius: 7px;
            border: 2px solid #fff;
            padding-left: 12px;
            padding-right: 12px;
            padding-top: 4px;
            padding-bottom: 4px;
        }
        .main_how{
            padding: 30px 0px 0px 40px;
            width: auto;
            height: 500px;
            background-color: white;
        }
        .main_movie{
            text-align: center;
            background-color: white;
        }
        .main_nft{
            margin-top: 40px;
        }
        .row{
            display: inline-block;
            width: 30%;
            margin:8px;
            padding: 16px;
            text-align: center;
        }
        .cols{
            display: inline-block;
        width: 49.80%;
        height: 350px;
        background-color: brown;
        }
        .features__left{      
            background-image: url(../Images/Dardevil.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position:top center ;

        }   
        .features__right{
            background-color: white;
            padding: 40px;
            vertical-align: top;
            text-align: left;
        }

    </style>
</head>
<body>
    <header>
        <div class="header_app">
            <a href="#" id="header_logo">MovieApp</a>
            <nav class="main_nav">
                <ul class="main_nav_lists">
                    <li id="main_nav_list">
                        <a href="#">Movie</a>
                    </li>
                    <li id="main_nav_list">
                        <a href="#">About Us</a>
                    </li>
                    <li id="main_nav_list">
                        <a href="#" id="main_nav_list_login">Login</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
    <main>
        <div class="main_how">
            <h1>How It Works</h1></div><hr>
            <div class="main_movie">
                <h1>Welcome To Movie App</h1>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Est odit tempora quidem quos ad reiciendis.</p>
                <div class="main_nft">
                    <div class="row" >
                        <i class="fa-solid fa-right-to-bracket fa-3x"></i>
                        <h1>Login</h1>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, nobis. Rem magni obcaecati minima possimus.</p>
                    </div>
                    <div class="row">
                        <i class="fa-brands fa-buffer fa-3x"></i>
                        <h1>Choose A Plan</h1>
                        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Debitis ullam similique dolor atque asperiores laborum.</p>
                    </div>
                    <div class="row">
                        <i class="fa-solid fa-film fa-3x"></i>
                        <h1>Enjoy The Movie</h1>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Id possimus dolorem omnis ducimus soluta minima.</p>
                    </div>
                    </div>
            </div><hr>
    </main>
    <div class="image_and_texts">
        <div class="cols features__left"></div>
            <div class="cols features__right" style="background-color:chocolate ;">
                <h1>Watch all Movies & TV Shows once they get released!</h1><br><br>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Soluta culpa totam reprehenderit commodi architecto odit non cum deleniti quasi error?</p><br><br>
                <div class="buttoni">
                    <a href="#" style="text-decoration: none; color: whitesmoke
                    ; background-color: tomato;padding: 8px 8px; border-radius: 5px;">View Features</a>
            </div>
            </div>
            </div>
</body>
</html>
