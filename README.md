# Redbull
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Redbull Schools</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <style type="text/css">
        body{
            padding: 0;
            margin: 10px;
        }
        h1{
            color: brown;
        }
        .header {
            background-image: url(images/background.jpg);
            background-position: center;
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: scroll;
            box-sizing: border-box;
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
           
            


        }
        .menubar{
            
            text-align: center;
            text-decoration: none;
            

        }
        .menubar ul{
            display: inline-flex;
            list-style: none;
            color: white;
            background-color: brown;
        
            
        }
        .menubar li{
            width: 220px;
            margin: 10px;
            padding: 10px;
           
        }
        .menubar ul li a{
            text-decoration: none;
            color: white;
        }
       .active, .menubar ul li:hover{
           background: rgb(36, 19, 19);
           border-radius: 3px;
       }
       .menubar .fa {
           margin-right: 8px;
       }
       .submenu1{
           display: none;
       }
       .menubar ul li:hover .submenu1 {
           display: block;
           position: absolute;
           background: brown;
           margin: top 7px;
           margin-left: 7px;
       }
       .menubar ul li:hover .submenu1 ul{
           display: block;
           margin: 10px;
       }
       .menubar ul li:hover .submenu1 ul li{
           width: 150px;
           padding: 10px;
           border-bottom: 1px dotted white;
           background: transparent;
           border-radius: 0;
           text-align: left;
       }
       .menubar ul li:hover .submenu1 ul li a:hover {
            color: yellow;
       }
       .container h1 {
         font-size: 60px;
         font-weight: 900;
         margin-top: 24px;
         margin-bottom: 15px;
         color: yellow;
       }
       .container p {
         font-size: 40px;
        color: black;
        margin-top: 0;
       }
       .container{
           margin-left: 55%;
       }
       .button .btn{
            display: inline-block;
            background: linear-gradient(45deg, #bec4cd, #b6ac1b);
            border-radius: 6px;
            padding: 10px 20px;
            text-decoration: none;
            box-sizing: border-box;
            color: rgb(5, 0, 0);
            box-shadow: 3px 8px 22px gray;

       }
      

    </style>

</head>
<body>
    <div class="header">
<div class="menubar">
    <ul>
        <li class="active"><i class="fa fa-home"></i><a href="#">Home</a></li>
        <li><i class="fa fa-users"></i><a href="#">About Us</a>
            <div class="submenu1">
                <ul>
                    <li><i class="fa fa-road"></i><a href="#">Mission</a></li>
                    <li><i class="fa fa-eye"></i><a href="#">Vision</a></li>
                    <li><i class="fa fa-gavel"></i><a href="#">Privacy Policy</a></li>
                    
                </ul>
            </div>
        </li>
        
        <li><i class="fa fa-briefcase"></i><a href="#">Services</a>
            <div class="submenu1">
                <ul>
                    <li><i class="fa fa-leanpub"></i></i><a href="#">Online Education</a></li>
                    <li><i class="fa fa-graduation-cap"></i><a href="#">Scholarships Processing</a></li>
                    <li><i class="fa fa-american-sign-language-interpreting"></i><a href="#">Mentorship</a></li>
                    
                </ul>
            </div>
        </li>
        <li><i class="fa fa-phone"></i><a href="#">Contact</a></li>
        <li><i class="fa fa-ban"></i><a href="#">Disclaimer</a></li>
        
                    
    </ul>
</div>
<br>
<br>
<br>

<div class="container">
<h1>Learning Hills <br> Foundation</h1>
<p>Redbull Schools</p>

<div class="button">
    <a href="#" class="btn">Register your kid</a>

</div>

</div>
</div>


</body>
</html>
