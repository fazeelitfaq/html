# html-css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Circles</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
    <div class="maincircle">
        <div class="circle">100</div>
        <div class="circle">200</div>
        <div class="circle">300</div>
        <div class="circle">400</div>
    </div>
</div>
    
</body>
</html>


.body{
    margin: 0;
}
.main{
    width:400px;
    height:400px;
    margin:0 auto;
}
.maincircle{
    width:400px;
    height:400px;
    background-color: black;
    margin:0 auto;
    border-radius: 360px;  
    display:flex;
    justify-content: space-between;
    align-items: center;
}
.circle{
    width:60px;
    height:60px;
    background-color: white;
    border-radius: 360px;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
}
