<!DOCTYPE html>
<html lang="ru">
    <head>
        <link rel="stylesheet" href="dogs.css">
        <meta charset = "utf-8">
        <title>Dogs</title>
        <meta name="viewport" content="width=device-width">
    </head>
    <style>
    section{
    height: 100vh;
}
header{
    background-color:darksalmon;
    height: 50px;
    position: fixed;
    width: 100%;
    transition: 1s;
    overflow: hidden
}

header:hover{
    height: 150px;
    transition: 1s
}

a{
    font-family: fantasy;
    text-decoration: none;

}

section{
    padding-top: 30px;
}

@keyframes sec{
    from{
        background-image: url(super/photo_2020-04-23_17-20-26.jpg)
    }
    25%{
        background-image:url(super/photo_2020-04-23_17-20-24.jpg)   
    }
    50%{
        background-image:url(super/po.jpg)
    }
    75%{
        background-image:url(super/photo_2020-04-23_18-09-00.jpg);
    }
    to{
        background-image: url(super/photo_2020-04-23_17-20-26.jpg)
    }
}

.sec1{
    animation: sec 20s infinite;
    background-size: 1280px 850px;
    padding-top: 50px;
}

h1{
    align-content: center;
    text-align: center;
    font-family: cursive;
}

h2{
    align-content: center;
    text-align: center;
}

h3{
    font-size: 30px;
    text-align: center;
}

body{
    margin: 0;
}

.sec2{
}

.sec3{
    background-color: 
}

.div{
    height: 100%;
    width: 33%;
    display: inline-block;
    background-color: peachpuff;
}

div{
    height: 80%;
    display: inline-block;
}

.a1{
    background-image: url(super/x_857b4682.jpg);
    width: 25%;
}

.a2{
    width: 73%;
    background-color: dimgrey;
}

img{
    background-size:400px 300px; 
}

.sec4{
    background-color:floralwhite;
}

footer{
    background-color:white;
}
    </style>
    <body>
        <header>
            <h2>Navigation menu</h2>
            <nav>
                <ul>
                    <li><a href="#2">Main Information</a></li>
                    <li><a href="#3">Photo Gallery</a></li>
                    <li><a href="#4">Contacts</a></li>
                </ul>
            </nav>
        </header>
        <section class="sec1">
            <h1>YOUR BEST FRIEND`S SECRETS</h1>
            <p></p>
        </section>
        <section class="sec2" id="2">
            <div class="div"><h3>Info</h3></div>
            <div class="div"><h3>Info</h3></div>
            <div class="div"><h3>Info</h3></div>
        </section>
        <section id="3" class="sec3"></section>
        <section id="4" class="sec4">
            <h3>Contacts</h3>
            <div class="a1"></div>
            <div class="a2"></div>
        </section>
        <footer>
            <p>Author: Anastasia</p>
            <p>Сreator:Elisey Shinkarev</p>
        </footer>
    </body>
</html>
