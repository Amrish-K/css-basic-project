### AIM:
Design a website like the one given below
### contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 40px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:papayawhip;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:whitesmoke;
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height: 30px;
        bottom: 0;
        width: 100%;
        color: white;
        position: absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color:  black;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: wheat;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:30px;
        }
        .coform form input{
            margin-left: 10px;
            width:500px;
            height:25px;
        }
        .coform form textarea{
            margin-left: 5px;
        }
        .coform form button{
            position: absolute;
            background-color: tan;
            color:black;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:44.2%;
            font-size: 20px;
            background-color: rgba(0, 0, 0, 0.781);
            padding:70px 250px 95px 147px ;
            margin-left: 840px;
            color: white;
            border: 4px;
            border-color: beige;
            border-style: solid;
        }
        .coform form{
            background-color:rgba(0, 0, 0, 0.781) ;
            color: aliceblue;
            top:44.3%;
            margin-left: 20px;
            padding:0px 282px 50px 0px;
            border: 4px;
            border-color: tan;
            border-style: solid;
        }
        .u{
            text-align: center;
            font-size: larger;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>ELITE</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="exstayre.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                
                <div class="coform">
                    <form>
                      <h3>&nbsp;Contact Us</h3>
                      <input type="text" placeholder="Your Name"><br><br>
                      <input type="text" placeholder="Your Email"><br><br>
                      <textarea rows="12" cols="66" ></textarea><br>
                      <button id="submit">Submit</button>
                    </form>
                </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br0>
            <b>Address: </b>17/3, 1st Floor, 2nd Cross Street, Barathiyar Nagar, Avadi , Chennai, Tamil Nadu<br><br>
            <b>Email: </b>kripalamrish90@gmail.com<br><br>
            <b>Phone: </b>7010556176
        </div>
       
    </div>
                <footer class="u">
                    Designed and Developed by Amrish&copy;2024
                    </footer>
                   
    </body>
    </html>
```
###exstarye:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Myfirstwebsite</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        h1 {
            color: black;
            font-size: 45px;
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: papayawhip;
            margin: 0;
           
}
        

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 255, 255);

        }

        .navbar a {
            color: rgb(0, 0, 0);
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color:powderblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: black;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 55px;
            background-color: white;
            margin-left: 10px;
            
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: white;
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: black;
            margin-top: 10px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color:rosybrown;
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: burlywood;
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color: white;
            background-color:sandybrown;
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color:wheat;
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color:rgba(0, 0, 0, 0.781);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color:sandybrown;
            margin-right: 50px;
            color: white;
            padding: 10px 35px 10px 35px;
            font-size: 15px;
            border-radius: 15%;
            width: 60%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 5px 30px 5px 30px;
            background-color: rgb(133, 155, 155);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 15px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 65px;
        }

        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 40px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .t{
            text-align: center;
            font-size: larger;
        }
        .d{
            margin-left: 10px;
            color:chocolate;
        }

    </style>
</head>

<body>
    <header>
        <h2>ELITE</h2>
    </header>
    <nav class="navbar" >

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="exstayre.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1 align="top">
        <div class="first">Learn to Code!!
            </div>
        <div class="second">Connecting Coders, Building Better Tomorrow.</div>
    </h1>
    <div class="d">
        <p> &nbsp;The zenith of coding websites lies not only in the lines of code but in the vibrant tapestry of a community<br>&nbsp;passionately innovating and evolving.</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <a href="" style="padding-right: 25px; color: aliceblue;"><i class="bi bi-google"></i></a>
                <a href="" style="padding-right: 25px; color: aliceblue;"><i class="bi bi-facebook"></i></a>
                <a href="" style="padding-right: 20px; color: aliceblue;"><i class="bi bi-twitter"></i></a>
            </div>
            
        </form>
    </div>
    <footer class="t">
        Designed and Developed by Amrish,2024
    </footer>

</body>
</html>
```
###people.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 30px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:papayawhip;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color: white;        
        }
        .navbar a{
         color:rgb(0, 0, 0);
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:orangered;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color:red;
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:190px;
           height:190px;
           margin:10px
        }
        .border{
        border-width:2px;
        border-color:black;
        border-style:solid;
        border-radius:50%;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 70px;
            
        }
        .text{
            position:absolute;
            top:55%;
            margin-left:35px;
            font-size:20px;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:58px;
            font-size:20px;
        }
        .class{
            text-align: center;
            font-size: larger;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>ELITE</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="pass photo 3.jpg" width="500px">
            <img class="small border" src="pass photo1.jpg" width="500px" >
            <img class="small border" src="pass photo2.jpg" width="500px">
            <img class="small border" src="pass photo3.jpg" width="500px">
            <img class="small border" src="images.jpg" width="500px">
            
            
        </div>
        <div class ="text">
            <table cellpadding="70">
                <tr class="head">
                    <th>RAMESH</th>
                    <th>RAM</th>
                    <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;RAHUL</th>
                    <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;HARISH</th>
                    <th>&nbsp;&nbsp;&nbsp;VIKAS</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="68">
                <tr>
                    <td>FOUNDER</td>
                    <td>CO-FOUNDER</td>
                    <td>CEO</td>
                    <td>DIRECTOR</td>
                    <td>MANAGER</td>
                    
                </tr>
            </table>
        </div>
      
            <footer class="class">
                Designed and Developed by Amrish,2024
                </footer>
               
</body>
</html>
```
###products.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: black;
        font-size: 45px;
        font-family:'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:papayawhip;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:whitesmoke;
        
        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:yellow;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:black;
        font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        font-size:55px;
        background-color:white;
        }
        footer{
        background-color:black;
        height:30px;
        bottom: 0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:white;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:black;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: yellowgreen;
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .contain{
                position: absolute;
                top:12%;
                width:1240px;
                height:750px;
                margin-left: 90px;
               margin-top: 28px;
                background-color:papayawhip;
                font-size: larger;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                
                
                }
                .contain p b{
                    font-size: 30px;
                    padding-left: 45px;
                }
                .contain p{
                    font-size: 18px;
                    padding-left: 10px;
                    padding:5px 20px 0px 15px ;
                    
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
                .m{
                    text-align: center;
                    font-size: large;
                }

    </style>
</head>
<body>
    <header>
        <h2>ELITE</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="products.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="exstayre.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="c++ logo.png" height="200px" width="200px">
                            <p><b>WEBDESIGN&nbsp;</b><br>
                                
                               
                
                        </p></td>
                        <td><img src="python.png" height="200px" width="200px"><br>
                            <p><b>JAVASCRIPT&nbsp;</b><br>
                                
                                
                        </p></td>
                        <td><img src="web design.png" height="200px" width="200px"><br>
                            <p><b>PYTHON <br>
                        
                        </p></td>
                        <td><img src="java logo.png" height="200px" width="200px"><br>
                            <p><b>JAVA</b><br>
                               
                                
                        </p></td>
                        <td><img src="js logo.png" height="200px" width="200px"><br>
                            <p><b>C/C++</b><br>
                                
                                
                        </p></td>  
                    </tr>
                    <tr>
                        
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer class="m">
                Designed and Developed by Amrish,2024
                </footer>
               
</body>
</html>
```
###OUTPUT:

![Screenshot (37)](https://github.com/Amrish-K/css-basic-project/assets/130633944/a12da716-9160-45c4-aa53-80a0de965e73)
![Screenshot (38)](https://github.com/Amrish-K/css-basic-project/assets/130633944/bbf4bd72-a0f7-4063-9374-a6ba28215f37)
![Screenshot (39)](https://github.com/Amrish-K/css-basic-project/assets/130633944/ade88cc4-e93d-462a-9868-98254c611b70)
![Screenshot (40)](https://github.com/Amrish-K/css-basic-project/assets/130633944/e9a952ff-0e64-42b0-a8a5-da26d11b7966)
### RESULT:
Thus, the website using CSS was created successfully.


