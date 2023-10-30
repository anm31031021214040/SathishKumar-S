
<!DOCTYPE html>
<html>
<head>
<title>YourName - Portfolio</title>
<style>
body{
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color:#f0f0f0 ;
}
header{
background-color:#333;
color:#fff;
text-align: center;
padding: 2rem 0;
position: relative; /*Add this*/
}
.header-content h1 {
font-size: 2.5rem;
}

/*Add styles for the round profile picture*/
.profile-pricture {
width: 100px; /*Adjust the size as needed*/
height: 100px;
border-radius: 75%;/*create a circlar shape*/
object-fit: cover; /*To ensure the image fills the circular area*/
position: absolute; /*Add this*/
top: 75px; /*Adjust top position as needed*/
left: 75px; /*Adjust left position as needed*/
}

nav {
background-color: #333;
color: #fff;
text-align: center;
}
nav ul {
list-style-type: none;
padding: 0;
}

nav ul li {
display: inline;
margin: 0 20px;
}

nav ul li a {
text-decoration: none;
color: #fff;
}

.section-content {
background-color: #fff;
padding: 2rem;
margin: 1rem;
border-radius: 20px;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.download-button {
background-color: #333;
color: #fff;
padding: 0.5rem 1rem;
text-decoration: none;
border-radius: 20px;
display: inline-block;
margin-top: 10px;
}

.download-button:hover {
background-color: #555;
}

footer {
text-align: center;
padding: 1rem 0;
background-color: #333;
color: #fff;
}

ul {
list-style-type: square;
padding-left: 20px;
}
</style>
</head>
<body>
<header>
<div class="header-content">
<!-- Add your profile pricture -->
<img src="Lokeshwari A.jpeg" alt ="your profile pricture" class="profile-pricture">
<hl>Lokeshwari A</hl>
<P>Passionate on Student</P>
</div>
</header>

Line wrap
<!DOCTYPE html>
<html>
<head>
<title>YourName - Portfolio</title>
<style>
body{
font-family: Arial, sans-serif;
margin: 0;
padding: 0;
background-color:#f0f0f0 ;
}
header{
background-color:#333;
color:#fff;
text-align: center;
padding: 2rem 0;
position: relative; /*Add this*/
}
.header-content h1 {
font-size: 2.5rem;
}

/*Add styles for the round profile picture*/
.profile-pricture {
width: 100px; /*Adjust the size as needed*/
height: 100px;
border-radius: 75%;/*create a circlar shape*/
object-fit: cover; /*To ensure the image fills the circular area*/
position: absolute; /*Add this*/
top: 75px; /*Adjust top position as needed*/
left: 75px; /*Adjust left position as needed*/
}

nav {
background-color: #333;
color: #fff;
text-align: center;
}
nav ul {
list-style-type: none;
padding: 0;
}

nav ul li {
display: inline;
margin: 0 20px;
}

nav ul li a {
text-decoration: none;
color: #fff;
}

.section-content {
background-color: #fff;
padding: 2rem;
margin: 1rem;
border-radius: 20px;
box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.download-button {
background-color: #333;
color: #fff;
padding: 0.5rem 1rem;
text-decoration: none;
border-radius: 20px;
display: inline-block;
margin-top: 10px;
}

.download-button:hover {
background-color: #555;
}

footer {
text-align: center;
padding: 1rem 0;
background-color: #333;
color: #fff;
}

ul {
list-style-type: square;
padding-left: 20px;
}
</style>
</head>
<body>
<header>
<div class="header-content">
<!-- Add your profile pricture -->
<img src="Lokeshwari A.jpeg" alt ="your profile pricture" class="profile-pricture">
<hl>Lokeshwari A</hl>
<P>Passionate on Student</P>
</div>
</header>

<nav>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#resume">Resume</a></li>
</ul>
</nav>

<section id="about">
<div class="section-content">
<h2>About Me</h2>
<p>Hello Everyone This is Lokeshwari A and i am a computer science student.</p>
</div>
</section>
<section id="education">
<div class="section-content" >
<h2>B.SC.,</h2>
<p>Kallakurichi Government Arts and Science College-CS</p>
</div>
</section>

<section id="skills">
<div class="section-content">
<h2>skills</h2>
<ul>
<li>c</li>
<li>c++</li>
<li>Java Programming</li>
<li>Python</li>
<li>Deep Learning</li>

</ul>
</div>
</section>

<section id="projects">
<div class="section-content">
<h2>Projects</h2>
<ul>
<li><a herf="#">Project 1</a></li>
<li><a herf="#">Project 2</a></li>
<!-- Add more projects links here -->
</ul>
</div>
</section>

<section id="resume">
<center>
<dic class="section-content">

</dic>
</center>
</section>

<footer>
<p>&copy; 2023 Lokeshwari A</p>
</footer>

<script>
// smooth scrolling to section when clicking on Lokeshwari A links
document.querySelectorAll( 'a[herf^="#"]').forEach(anchor => {
anchor.addEventLister('click',function(e){
e.PreventDefult();

const targetId = this.getAttribute('herh').substring(1);
const targetElement = document.getElementById(targetId);
if (tarfetElement) {
window.scrollTo({
top: targetElemnt.offsetTop,
behavior: 'smooth'
});
}
});
});
</script>
</body>
</html>￼Enter<nav>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#education">Education</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#resume">Resume</a></li>
</ul>
</nav>

<section id="about">
<div class="section-content">
<h2>About Me</h2>
<p>Hello Everyone This is Lokeshwari A and i am a computer science student.</p>
</div>
</section>
<section id="education">
<div class="section-content" >
<h2>B.SC.,</h2>
<p>Kallakurichi Government Arts and Science College-CS</p>
</div>
</section>

<section id="skills">
<div class="section-content">
<h2>skills</h2>
li>c</li>
<li>c++</li>
<li>Java Programming</li>
<li>Python</li>
<li>Deep Learning</li>

</ul>
</div>
</section>

<section id="projects">
<div class="section-content">
<h2>Projects</h2>
<ul>
<li><a herf="#">Project 1</a></li>
<li><a herf="#">Project 2</a></li>
<!-- Add more projects links here -->
</ul>
</div>
</section>

<section id="resume">
<center>
<dic class="section-content">

