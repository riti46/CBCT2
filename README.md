<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sejal's personal portfolio</title>
    <link rel="poppins" href="https://fonts.google.com/specimen/Poppins?query=po">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: black;
            color: white;
            font-family: 'poppins';
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: goldenrod;
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
            color: darkblue;
            font-size: 1.04rem;
            /* background-color: lightseagreen; */
        }

        main hr {
            border: 0;
            background: #9c979c;
            height: 1.2px;
            margin: 60px 84px;
        }

        .left {
            font-size: 2rem;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            color: black;
            /* background-color: lightseagreen; */
            /* border-radius: 10px; */
        }

        .firstsection {
            display: flex;
            align-items: center;
            justify-content: space-around;
            margin: 140px 0;
            font-size: medium;
        }

        .firstsection>div {
            width: 30%;
        }
        
        .leftsection {
            font-size: 3rem;
            padding: 23px;
            font-family: 'Times New Roman', Times, serif;
            
        }

        .leftsection .button{
            padding: 50px 0;
        }

        .leftsection .btn {
            padding: 12px;
            background: blueviolet;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
        }

        .leftsection .btn:hover{
            background-color: blanchedalmond;
            color: black;
            border-color: black;
            
        }

        .rightsection img {
            width: 80%;
            border: 10px solid goldenrod;
            border-radius: 285px;
            
            /* margin-left: 0 100px ; */
            /* padding: 50px; */

        }

        .purple {
            color: blueviolet;
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: blueviolet;
        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondsection h1 {
            font-size: 1.6rem;
            color: aqua;
        }

        .secondsection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 58px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 10px;
            background-color: white;
            margin: 0 100px;
        }

        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }

        /* .vertical-title {

            position: relative;
            top: 75px;
            margin-top: 200px;
            width: 150px;
        }

        .vertical-desc {
            margin-top: 1px;
        } */
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">RITIKA's PORTFOLIO</div>
            <div class="right">
                <ul>
                    <li> <a href="/">HOME</a></li>
                    <li> <a href="/">ABOUT</a></li>
                    <li> <a href="/">SERVICES</a></li>
                    <li> <a href="/">PROJECTS</a></li>
                    <li> <a href="/">CONTACT ME</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">Hi my name is <br><span class="purple">Ritika Chourasiya</span>
                <div>and I'm a passionate </div>
                <!-- <div>Web Developer</div> -->
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn">Visit Github</button>
                </div>

            </div>
            <div class="rightsection">
                <img src="ritika.jpeg" alt="">
                <!-- <div class="vertical-title">
                    HTML Developer (2010-2012)
                </div> -->
                <!-- <div class="vertical-desc">
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate repudiandae nostrum, eligendi
                    blanditiis, inventore consequuntur pariatur praesentium est, dicta iure culpa cum nobis!
                </div> -->
            <!-- </div>
            <div class="vertical">
                Node.js Developer (2012-2014)
            </div> -->
        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray">What i have done so far</span>
            <h1>Education</h1>
            <br>
            <ol>
                <li>12th pass from MP board</li>
                <li>Currently in 7th semester </li>
                <li>Branch-Computer Science</li>
                <li>College-Bansal institute of research and technology</li>
            </ol>
            <br>
            <h1>Skills</h1>
            <br>
            <ol>
                <li>Html,Css,Js</li>
                <li>SQL,MS word, Power Point</li>
                <li>C,C++</li>
                <li>Cyber Security</li>
                <li>Project Management</li>
            </ol>
            <br>
            <h1>Contact Me</h1>
            <br>
            <ul>
                <li>+91 8770265494</li>
            </ul>
            <br>
            <h1>Address</h1>
            <br>
            <ul>
                <li>B-19 sarvjan colony lalita nagar kolar road Bhopal(MP)</li>
            </ul>




            <!-- <div class="box">
                <div class="vertical">
                    <img class="image-top"
                        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDzb2XG8k9-2fI7pFIVOzW9gnZxNJy4R7E1rGQGaYw0w&s"
                        alt=""> -->
                <!-- </div>
                <div class="vertical"></div>
                <div class="vertical"></div>
                <div class="vertical"></div>
            </div> -->

        </section>
    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('#element', {
            strings: ['Front-End Web Developer'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
