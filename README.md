<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anushka-developer portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lugrasimo&family=Oswald&family=Poppins:wght@700&family=Tektur&family=Ubuntu&family=VT323&family=Varela+Round&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            padding: 0;
        }
body{
    background-color: rgb(99, 10, 131);
    color: white;
    font-family: 'Poppins',sans-serif;
}

nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 80px;
    background-color: rgb(165, 68, 184);
}
nav ul{
    display: flex;
    justify-content: center;
}
nav ul li{
    list-style: none;
    margin: 0 23px;
}
nav ul li a{
    text-decoration: none;
    color:white
}
nav ul li a:hover{
    
    color:  rgb(248, 160, 175)
}
main hr{
    border: 0;
    background: #9c97f1;
    height: 1.2px;
    margin: 40px 84px;
}
.left{
    font-size: 1.6rem;
}

.firstsection{
    display: flex;
    justify-content: space-around;
    margin: 80px 0;
}

.firstsection > div{
    width: 30%;
}

.leftsection{ 
    font-size: 3rem; 
    margin: 50px 0;
}
.leftsection.buttons{
    padding: 50px;
}
.leftsection .btn{ 
    padding: 12px;
    background-color: #b09bc0;
    border: 2px soild white;
    border-radius: 6px;
    font-size: 20px;
    cursor: pointer;
}


.righttsection img{
    width: 80%;
          
}
.purple{
    color: blueviolet;
}
.text-gray{
    color: #c08bd2;
}
#element {
    color: rgb(248, 160, 175)
}
.secondSection{
    max-width: 80vw;
    margin: auto;
    height: 80vh;
}
.secondSection h1{
    font-size: 1.9rem;
}
.secondSection .box{
    background: white;
    width: 80vw;
    height: 2px;
    margin: 56px 0;
    display: flex;
}
.secondSection .vertical{
    height: 93px;
    width: 1px;
    background-color: white;
    margin: 0 120px;
}
.image-top{
    width: 23px;
    position: relative;
    top: -32px;
    left: -9px;
}
.vertical-title{
    position: relative;
    top: 75px;
    width: 150px;
    font-size: 14px;

}
.vertical-desc{
    position: relative;
    top: 86px;
    color:blue;
    width: 150px;
    font-size: 9px;
}
footer{
    background-color: rgb(185, 100, 207);
    height: 100px;
}
.footer{
    display: flex;
    margin: 23px 122px;
    justify-content: space-evenly;
}
.footer ul{
    list-style: none;
}
.footer > div{
    width:123px;
}
footer .footer-rights{
    text-align: center;
}
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Anushka's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contacts</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi My name is <span class="purple">Anushka</span>
                
                <div>and im a web developer</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download resume</button>
                    <button class="btn">Visit github</button>
                </div>
            </div>

            <div class="rightsection">
                <img src="devgirl.png" alt="">
            </div>

        </section>
        <hr>
        <section class="secondSection">
            <span class="text-gray"> What i have done so far</span>
            <h1>Past experiences</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="devgirl.png" alt="">
                    <div class="vertical-title">
                        HTML DEVELOPER (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    NODE JS DEVELOPER (2010-2012)
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="devgirl.png" alt="">
                    <div class="vertical-title">
                        HTML DEVELOPER (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    gjhg jk kjlkf liej
                    rtgergtht
                    thttfd
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="devgirl.png" alt="">
                    <div class="vertical-title">
                        HTML DEVELOPER (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    NODE JS DEVELOPER (2010-2012)
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="devgirl.png" alt="">
                    <div class="vertical-title">
                        HTML DEVELOPER (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    NODE JS DEVELOPER (2010-2012)
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="devgirl.png" alt="">
                    <div class="vertical-title">
                        HTML DEVELOPER (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    NODE JS DEVELOPER (2010-2012)
                    </div>
                </div>
            </div>
        </section>
    </main>
<footer>
<div class="footer">
    <div class="footer-first">
        <h3>Anushka developer portfolio</h3>
    </div>
    <div class="footer-second">
        <ul>
            <li>Home</li>
            <li>about</li>
            <li>Services</li>
            <li>Contact</li>
        </ul>
    </div>
    <div class="footer-third">
        <ul>
            <li>Home</li>
            <li>about</li>
            <li>Services</li>
            <li>Contact</li>
        </ul>
    </div>
    <div class="footer-forth">
        <ul>
            <li>Home</li>
            <li>about</li>
            <li>Services</li>
            <li>Contact</li>
        </ul>
    </div>
</div>
<div class="footer-rights">
    www.anushkaportfolio.com
</div>
<footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
          strings: ['web developer','Graphic designer','web designer','Video editor'],
          typeSpeed: 50,
        });
      </script>
</body>
</html>
