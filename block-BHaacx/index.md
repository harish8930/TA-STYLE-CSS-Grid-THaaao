<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>

<div class="container">
<div class="item1">
<img class="head-img" src="https://github.com/harish8930/TA-STYLE-CSS-Grid-THaaao/blob/block-BHaacx/block-BHaacx/assets/media/home-img.jpg?raw=true" alt="error">
</div>

<div class="item2">
<div class="inner">
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About Me</a></li>
    <li><a href="#">Experiences</a></li>
        <li><a href="#">Testimonial</a></li>
        <li><a href="#">Contact</a></li>
</ul></div>
<div class="stimulus">
<h3>Welcome to my Website</h3>
<h1>Hello,I am <em>Stimulus</em> currently based in New York City</h1>
<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Hic recusandae rerum, odio suscipit perspiciatis cumque doloremque exercitationem culpa consectetur optio!</p>
<button>Get Started</button></div>
</div>
</div>
</header>


<div class="skill">

<div class="item3">
<h2 class="ith3">Donec auctor</h2>
<p class="upp">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
<p class="itp">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Distinctio recusandae labore voluptates autem saepe quod eos molestias voluptatum officia natus.</p>
<p class="itpp">Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur, quidem.</p>
</div>

<div class="item4">
    <img class="skillimg" src="https://github.com/harish8930/TA-STYLE-CSS-Grid-THaaao/blob/block-BHaacx/block-BHaacx/assets/media/about-img.jpg?raw=true" alt="error">
</div>
<div class="item5">
<h2 class="skill-head">My Skills</h2>
<p class="skills">PHOTOSHOP,HTML,CSS,JS,WEB DESIGN</p>

</div>
</div>


<script src="script.js"></script>

</body>
</html>


style.css
/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
/*starts here*/
*{
    margin: 0px;
}
.container{
    display: grid;
    grid-template-columns: repeat(2,600px);
    max-width: 1200px;
    margin: 0 auto;

}

.head-img{
    width: 100%;
    height: 550px;
}
.inner ,ul,li,a{
display: flex;
text-decoration: none;
text-transform: uppercase;
margin-left: 10px;
font-size: 12px;
color: gray;
}
ul{ margin-left: 50px;
    margin-top: 20px;
}
.item2{background-color: rgb(228, 191, 191);
height: 550px;
}
h3{font-size: 15px;
margin-bottom: 20px;}
h1{
    font-size: 25px;
    margin-bottom: 20px;
    color: black;
    font-weight: 100;
}
.stimulus{
    width:400px;
    height: 300px;
    margin-top: 100px;
    margin-left: 30px;
    color: gray;
}

button{margin-top: 20px;
padding: 10px 30px;
border-radius: 10px;
background-color:  rgb(228, 191, 191);
border: 2px solid black;
}
a:hover{
    color: orange;
}
em{font-weight: 700;}

.skill{
    display: grid;
    grid-template-columns: 600px 300px 300px;
    margin-left: 75px;
}
.skillimg{width: 100%;
height: 200px;
}
.item3,.item4,.item5{
    width: 100%;
}
.item5{background-color: goldenrod;}
.ith3{font-size: 24px;
margin: 20px 0px;
}

.itp,.itpp{margin-top: 10px;
line-height: 1.3;
color: grey;
font-size: 18px;
}
.upp{color: orange;
font-size: 18px ;
}
.skill-head{
    font-size: 18px;
    color:white;
    margin: 20px 20px;
}
.skills{
    font-size: 12px;
    color: white;
    margin: 20px 20px;
}
.progress-bar {
    background-color: #f2f2f2;
    border-radius: 4px;
    height: 20px;
    margin-bottom: 10px;
    overflow: hidden;
  }
  
  .bar {
    background-color: #000000;
    height: 100%;
  }
  
  .label {
    color: #fff;
  display: block;
  font-size: 15px;
  font-weight: bold;
  padding: 0 5px;
  text-align: center; 
  }
