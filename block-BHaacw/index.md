HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Card Layout</h1>
    <script src="script.js"></script>
<header>
<div class="container">
<div class="navbar">
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Gallery</a></li>
<li><a href="#">Blog</a></li>
<li><a href="#">Refrence</a></li>
<li><a href="#">Contact</a></li>
</ul>
</div>
</header>


<div class="big-box">
<div class="item1">
    <h2>THE TITLE </h2>
<P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi voluptatum quasi rem. Amet, sequi cumque aut nisi quos iure vel!</P>
</div>

<div class="item2">
    <h2>THE TITLE</h2>
    <img src="https://t4.ftcdn.net/jpg/02/66/72/41/360_F_266724172_Iy8gdKgMa7XmrhYYxLCxyhx6J7070Pr8.jpg" alt="erorr"/>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam mollitia dolorum fuga voluptas, ducimus doloribus nostrum debitis molestiae iusto laborum!</p>
</div>

<div class="item3">
    <h2>THE TITLE</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus itaque perspiciatis nostrum ad sapiente unde harum alias hic rem nihil!</p>
</div>


<div class="item4">
    <h2>THE TITLE</h2>
    <img class="graph" src="https://images.emojiterra.com/google/noto-emoji/unicode-15/color/512px/1f4c8.png" alt="error">
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus itaque perspiciatis nostrum ad sapiente unde harum alias hic rem nihil!</p>
</div>

<div class="item5">
    <h2 class="heading">THE TITLE</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus itaque perspiciatis nostrum ad sapiente unde harum alias hic rem nihil!</p>
</div>
<div class="item6">
    <h2>THE TITLE</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Necessitatibus itaque perspiciatis nostrum ad sapiente unde harum alias hic rem nihil!</p>
</div>
</div>


</div>
</body>
</html>

CSS

body{
    background-color: rgb(105, 115, 124);
}


.container{max-width: 1300px;
}


.navbar ul {display: grid;
grid-template-columns: repeat(6,100px);
list-style: none;
justify-content: space-evenly;
font-size: 18px;
padding: 5px 5px;
color: rgb(102, 102, 255);
}

.navbar{
background-color: white;
width: 1000px;
margin: 0 auto;

}
a{text-decoration: none;}

.big-box{
    display: grid;
    grid-template-columns: 300px  300px 300px ;
    grid-template-rows: 150px 150px 150px;
   
    width: 1000px;
    margin: 0 auto;
    gap: 18px;
}
img{
    width: 200px;
    height: 200px;
    border-radius: 50%;
}
.item1,.item2,.item3,.item4,.item5,.item6{
    background-color: white;
    text-align: center;
    border-radius: 8px;
    border-top: 2px solid rgb(50, 50, 255);
}
h1{
    text-align: center;
    font-size: 28px;
}

.item2{grid-row: span 3;}
.item4{grid-row: span 2;}

.graph{width: 100px;
    height: 100px ;
    border-radius: none;
}
.heading{
    background-color: rgb(50, 50, 255);
    color: white;
}


