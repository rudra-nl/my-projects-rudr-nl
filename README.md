<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>YOGA IS LIFE</title>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@400..800&display=swap" rel="stylesheet">
    <!-- <link rel="stylesheet" href="style.css"> -->
  
</head>
<style>
    /* CSS Reset */
    

    body{
        font-family: 'Baloo Bhai 2',serif;
        color: rgb(69, 69, 241);
        margin: 0px;
        padding: 0px;
        background: url("https://thumbs.dreamstime.com/z/serenity-yoga-practicing-meditation-vector-illustration-original-paintings-drawing-97122190.jpg")
    }
    .left{
        display: inline-block;
        position: absolute;
        left: 24px;
        top: 13px;
        display: inline;
        border:  2px solid rgb(38, 218, 38);
    }
    .left img{
        width: 135px;
        filter: invert(100%);
    }
    .left div{
        text-align: center;
    }
    .mid{
        display: block;
        width:50%;
        margin: 14px auto;
        border:  2px solid rgba(33, 187, 207, 0.322);
    }
    .right{
        position:absolute;
        right: 24px;
        top: 13px;
        display: inline;
        border:  2px solid hwb(66 3% 1%);
    }
    .navbar{
        display: inline-block;
    }
    .navbar li{
        color: azure;
        display: inline-block;
    }
    .navbar li a{
        color: rgb(103, 80, 160);
        text-decoration: none;
        padding: 10px 10px;
        /* font-size: 15px; */
       
    }
    .navbar li a:hover , .navbar li a.active {
       text-decoration: underline;
       color: rgb(18, 18, 19);
       
       
    }
    .btn{
        margin:0px 10px;
        background-color: rgb(205, 243, 102);
        color: rgb(25, 0, 255);
        padding: 4px 15px ;
        border-radius: 25px;
        cursor: pointer;
    }
    .btn:hover{
        background-color: rgb(161, 151, 151);
    }
    
    .container {
        background-color: black;
        border: 2px solid green;
        margin: 20px 2px;
        padding: 25px;
        width: 33%;
        border-radius: 2px;
        border-radius: 25px;
    }
    .form-group input{
        background-color: wheat;
        text-align: center;
        display: block;
        width: 154px;
        padding: 6px;
        border: 2px solid black;
        margin:  3px auto;
    }
    .container h1 {
        text-align: center;

    }
    .form-group button{
        display: block;
        width: 23%;
        margin: auto;
    }

</style>

<body>
    <header class="header">
        <div class="left">
        <img src="img/logo.jpg" alt=""></div>
        <div> yoga and fitness

        </div>
          
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">HOME</a></li>
                <li><a href="#" > ABOUT US</a></li>
                <li><a href="#" >CONTRIBUTION</a></li>
                <li><a href="#">LOCATIONS</a></li>
                <li><a href="#">CONTACT US</a></li>
                </ul>
        </div>
        <div class="right">
          <button class="btn">CALL US</button>
          <button class="btn">EMAIL US</button>
    </header> 
    <div class="container">
        <h1>JOIN THE BEST YOGA CENTRE</h1>
        <form action="noaction.php" >
            <div class="form-group">
                <div>
                <input type="text" name="text" placeholder="ENTER YOUR NAME">
            </div>
            <div class="form group">
                <input type="text" name="text" placeholder="ENTER YOUR NAME">
            </div>
            <div class="form group">
                <input type="text" name="text" placeholder="ENTER YOUR NAME">
            </div>
            <div class="form group">
                <input type="text" name="text" placeholder="ENTER YOUR AGE">
            </div>
            <div class="form group">

                <input type="text" name="text" placeholder="ENTER YOUR GENDER">
            </div>
            <div class="form group">

                <input type="text" name="text" placeholder="ENTER YOUR LOCATION">
            </div>
            <button class="btn ">submit</button>


        </form>
    </div>


</body>

</html>
