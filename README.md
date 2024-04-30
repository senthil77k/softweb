# Ex.07 Software Product Company Website
## Date:
30.04.2024
## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
1.page (html)
```

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: rgb(0, 0, 0);
            font-size: 45px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: rgb(249, 249, 249);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: rgb(0, 0, 0);

        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: rgb(36, 34, 34);
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: monospace;
            font-size: 60px;
            background-color: rgb(0, 0, 0);
        }

        footer {

            text-align: center;
            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: rgb(255, 255, 255);
            position: absolute;

        }

        header {
            background-color: rgb(0, 0, 0);
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: rgb(255, 255, 255);
            margin-top: -4px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(10, 237, 97);
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
            border-color: rgb(255, 255, 255);
        }

        .d {
            margin-left: 10%;
            position: absolute;
            top: 65%;
            font-size: 20px;
        }

        .search input {
            right: 8%;
            width: 18%;
            height: 30px;

        }
        .search button{
            right: 4%;
        }

        .search button,
        .d button {
            color: white;
            background-color: rgb(7, 7, 7);
            padding: 5px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 20px 30px 20px 30px;
            border-radius: 30px;
            border-color: none;
        }
        #joinus {
            right: -160px;
            
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: rgb(255, 255, 255);
        }

        .login form {
            position: absolute;
            right: 2%;
            top: 25%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color: rgba(25, 23, 20, 0.6);
            padding: 80px 80px 200px 80px;
        }

        .login form button {
            background-color: rgb(0, 0, 0);
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
            background-color: rgb(248, 250, 250);
            text-align: center;
            margin-left: 18px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid rgb(244, 244, 244);
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
            color: rgb(0, 0, 0);
            margin-left: 20px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: rgb(0, 0, 0);
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
    </style>
</head>

<body>
    <header>
        <h2>CodeCrafters Studio</h2>
    </header>
    <nav class="navbar">

        <ul>
            <li><a href="products.html">Contact</a></li>
            <li><a href="people.html">Products</a></li>
            <li><a href="contact.html">People</a></li>
            <li><a href="page1.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1>
        <div class="first">Code Crafters: Building Tomorrow's</div>
        <div class="second"> Solution,Today!<br> </div>
        <div class="third"></div>
    </h1>
    <div class="d">
        <p> &nbsp;"In the world of software, deadlines are not suggestions; they are commitments."</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            <h4>Don't have an account</h4><br>
            <div class="Signup" ><b><a href="">Sign up</a></b> here</div>
            <h5><B>Login with</B></h5>
            <div class="image">
               
            </div>
        </form>
    </div>
    <footer>
    
        Designed and Developed by SENTHILKUMARAN C; 2024
    </footer>

</body>

</html>

```
2.contact
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        
        h1{
        color: blue;
        font-size: 40px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:25%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:rgb(24, 24, 24);
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(46, 45, 45);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:black;
        }
        footer{

        background-color:black;
        text-align: center;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:black;
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        top:-9px;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(24, 25, 25);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:rgb(27, 27, 27);
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:4px;
        border-color:rgb(14, 15, 15);
        border-style:solid;
        border-radius:80%;
        }
        .cirpic{
            position:absolute;
            top:30%;
            margin-left: 50px;
        }
        .text{
            position:absolute;
            top:50%;
            margin-left: 20px;
            font-size: 20px;
        }
        .text2{
            position:absolute;
            top:55%;
            margin-left:52px;
        }
    
    </style>
</head>
<body>
    <header>
        <h2>CodeCrafters Studio</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="products.html">Contact</a></li>
        <li><a href="people.html">Products</a></li>
        <li><a href="contact.html">People</a></li>
        <li><a href="page1.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="212223220103.png" width="500px">
            <img class="small border" src="ex7.4.jpeg" width="500px" >
            <img class="small border" src="ex7.9.jpeg" width="500px">
            <img class="small border" src="ex8.1.jpeg" width="500px" >
            <img class="small border" src="ex10.1.jpeg" width="500px">
            <img class="small border" src="ex3.3.jpeg" width="500px" >
        </div>
        <div class ="text">
            <table cellpadding="87">
                <tr div class="head">
                    <th>senthil</th>
                    <th>Elon X</th>
                    <th>Top G</th>
                    <th>Putin</th>
                    <th>Tripti</th>
                    <th>Tristan Tate</th>
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="83">
                <tr>
                    <td>CEO</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO<br>Co-Founder</td>
                    <td>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CTO<br>Co-Founder</td>
                    <td>Director</td>
                    <td>Asst.Director</td>
                    <td>Dy.Director</td>
                </tr>
            </table>
        </div>
      
            <footer>
                Designed and Developed by SENTHILKUMARAN C; 2024
                </footer>
               
</body>
</html>

```
3.product
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: rgb(0, 0, 0);
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:silver;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:rgb(0, 0, 0);
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(49, 50, 50);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:rgb(0, 0, 0);
        top: -15px;
        }
        footer{

        background-color:black;
        text-align: center;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:rgb(0, 0, 0);
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:10px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(0, 0, 0);
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
            top:31.3%;
        color:  rgb(0, 0, 0);
            width:100%;
            size:7px;
        }
        .coform {
            background-color: white;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:40%;
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
            margin-left: 10px;
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(0, 0, 0);
            color:white;
            border-radius: 20%;
            margin-left: 10px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        .vl{
            position:absolute;
            border-left: 3px solid rgb(0, 0, 0);
            height: 445px;
            margin-left: 750px;
            top:33%;
        }
        #ci{
            font-size: 30px;
            margin-left: 40px;
        }
        .info{
            position:absolute;
            top:33%;
            font-size: 25px;
            background-color: white;
            padding:20px 183px 40px 147px ;
            margin-left: 795px;
            bottom: 31.3px;
        }
        .coform form{
            background-color: white;
            top:33%;
            margin-left: 0px;
            padding:0px 190px 49.3px 0px;
            height: 400px;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>CodeCrafters Studio</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="products.html">Contact</a></li>
            <li><a href="people.html">Products</a></li>
            <li><a href="contact.html">People</a></li>
            <li><a href="page1.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                <div class="line">
                    <hr color="black">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="10" cols="80" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>Tech park,Bangalore<br><br>
            <b>Email: </b>CodeCrafters.Studio@gmail.com<br><br>
            <b>Phone: </b>044-8974
        </div>
        <div class="vl"></div>
    </div>
                <footer>
                    Designed and Developed by SENTHILKUMARAN C; 2024
                    </footer>
                   
    </body>
    </html>

```
4.product
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
        color: rgb(0, 0, 0);
        font-size: 45px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        position: absolute;
        top:35%;
        }
        body{
        background-color:lightgrey;
        margin:0;
        }
        .navbar ul{
        list-style-type:none;
        background-color:darkblue;
        
        }
        .navbar a{
         color:white;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:20px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:rgb(57, 59, 60);
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:monospace;
        font-size:60px;
        background-color:rgb(0, 0, 0);
        }
        footer{
        background-color:black;
        text-align: center;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:rgb(0, 0, 0);
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:white;
        margin-top:-10px;
        margin-left:12px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(0, 0, 0);
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
                top:10%;
                width:1100.2px;
                height:570px;
                margin-left: 0px;
                background-color:lightgrey;
                }
                .contain p b{
                    font-size: 25px;
                    padding-left: 35px;
                }
                .contain p{
                    font-size: 20px;
                    padding-left: 30px;
                    padding:8px 30px 0px 15px ;
                }
                .contain img{
                   margin-top: 7px;
                   padding-left: 10px;
                   padding:20px 50px 0px 20px;
                   height: 120px;
                   width: 120px;
                   
                }
    </style>
</head>
<body>
    <header>
        <h2>CodeCrafters Studio</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="products.html">Contact</a></li>
        <li><a href="people.html">Products</a></li>
        <li><a href="contact.html">People</a></li>
        <li><a href="page1.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="microsoft.png" height="200px" width="200px">
                            <p><b>Microsoft</b><br>
                                &nbsp;&nbsp;&nbsp;Game Development<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Platform
                        </p></td>
                        <td><img src="salesforce.png" height="200px" width="200px"><br>
                            <p><b>Salesforce</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud-based<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;CRM
                        </p></td>
                        <td><img src="wordpress.png" height="200px" width="200px"><br>
                            <p><b>WordPress</b><br>
                                &nbsp;&nbsp;&nbsp;Content Management <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  System
                        </p></td>
                        <td><img src="oracle.jpeg" height="200px" width="200px"><br>
                            <p><b>Oracle </b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;Project Management<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Tool
                        </p></td>
                        <td><img src="dropbox.png" height="200px" width="200px"><br>
                            <p><b>Dropbox</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud Storage<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Device
                        </p></td>  
                    </tr>
                    <tr>
                        <td><img src="google.jpeg" height="200px" width="200px">
                            <p><b>Google</b><br>
                                &nbsp;&nbsp;&nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tax Preparation<br>
                                &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Software
                        </p></td>
                        <td><img src="adobe.jpeg" height="200px" width="200px"><br>
                            <p><b>Adobe</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud-based<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;CRM
                        </p></td>
                        <td><img src="vmware.jpeg" height="200px" width="200px"><br>
                            <p><b>VMware</b><br>
                                &nbsp;&nbsp;&nbsp;Content Management <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  System
                        </p></td>
                        <td><img src="sap.png" height="200px" width="200px"><br>
                            <p><b>SAP SE</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;Project Management<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Tool
                        </p></td>
                        <td><img src="apple.png" height="200px" width="200px"><br>
                            <p><b>Apple</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud Storage<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Device
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer>
                Designed and Developed by SENTHILKUMARAN C; 2024
                </footer>
               
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-04-30 112407.png>)
![alt text](<Screenshot 2024-04-30 112419.png>)
![alt text](<Screenshot 2024-04-30 112434.png>)
![alt text](<Screenshot 2024-04-30 112502.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
