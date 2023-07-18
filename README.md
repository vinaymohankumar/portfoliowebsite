# portfoliowebsite
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinay kumar portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: auto;
            padding: auto;
        }

        body {
            background-color: black;
            color: white;
            font-family: 'Poppins', sans-serif;


        }

        nav {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 80px;
            background-color: rgb(55, 14, 157);
        }

        nav ul {
            display: flex;
            justify-content: center;

        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(153, 153, 226);
            font-size: 1.01rem;
        }

        .left {
            font-size: 1.3rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            margin: 110px 0;
        }

        .firstSection div {
            width: 4cap;
        }
        .leftSection {
            font-size: 2rem;
        }
        .leftSection .btn{
            padding:5px;
            background: rgb(68, 30, 179);
            color:white;
            cursor:pointer;
            border-radius: 6px;
            border: 2px solid white;
        }
        .leftSection .btn1{
            padding:5px;
            background: rgb(97, 32, 143);
            color:white;
            cursor:pointer;
            border-radius: 6px;
            border: 2px solid white;
        }
        
        .rightSection img {
            width: 80%;

        }

        .purple {
            color: blueviolet
        }

        #element {
            color: blueviolet;
        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
        }
        .aboutSection{
            padding:10px;

        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Vinaykumar's Portfolio</div>
            <div class="right">
                <ul>
                    </a>
                    <li><a href="/">Home</a></li>
                    </a>
                    <li><a href="/">Skills</a></li>
                    </a>
                    <li><a href="/">About</a></li>
                    </a>
                    <li><a href="/">Projects</a></li>
                    </a>
                    <li><a href="/">contact me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hello, I am <span class="purple">VinayKumar</span>
                and i am a
                <section class="leftSection">
                    
                    <span id="element"></span>
                    <div class="buttons">
                        <button class="btn">Resume  </button>
                        <button class="btn">Github  </button>
                        <button class="btn">Linkedin</button>
                 </section>
                        

            </div>
            </div>
            <div class="rightSection">
                <img src="C:\Users\Vinay Kumar\Desktop\port.website\WhatsApp Image 2023-07-18 at 10.59.49.jpg" height="300"
                    width="300">
            </div>

        </section>
        <section class="secondsection">
            <div class="leftSection">
                <span class="purple">skills</span>
                
                <section class="leftSection">
                    
                    <span id="element"></span>
                    <div class="buttons">
                        <button class="btn1">basic c</button>
                        <button class="btn1">c++    </button>
                        <button class="btn1">python </button></div>
                 </section>
                        

            
            </div>
            </section>
            <section class="secondsection">
                <div class="leftSection">
                    <span class="purple">About</span>
                    
                    <section class="leftSection">
                        
                        <span id="element"></span>
                        <div class="buttons">
                            <button class="btn1">SSLC  </button>
                            <button class="btn1">PUC   </button>
                            <button class="btn1">BE    </button></div>
                     </section>
                            
    
                
                </div>
                </section>
                <section class="secondsection">
                    <div class="leftSection">
                        <span class="purple">Projects</span>
                        
                        <section class="leftSection">
                            
                            <span id="element"></span>
                            <div class="buttons">
                                <button class="btn1">python</button>
                                <button class="btn1">webdevlopment</button>
                                <button class="btn1">minor</button></div>
                                <button class="btn1">major</button></div>
                         </section>
                                
        
                    
                    </div>
                    </section>
                    <section class="contact us">
                        <span class="pink">contact us</span>
                        <script src="https://sheetdb.io/s/f/uclt9us7z4kgr.js"></script>
                        
                    </section>
        

    </main>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['<i>Web developer</i>', '<i>Coder</i>', '<i>Web designer</i>'],
            typeSpeed: 70,
        });
    </script>

</body>

</html>
