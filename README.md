# The-Pioneer-s-School-System-
The Pioneer's School System is one of the leading educational institutions in Faisalabad, dedicated to providing quality education from Play Group to Matric. Our mission is to develop confident, responsible, and successful students through academic excellence, character building, and modern teaching methodologies.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Pioneer's School System</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f7fb;
color:#333;
}

nav{
position:fixed;
top:0;
width:100%;
background:#002b80;
padding:15px 5%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

nav .logo{
color:#fff;
font-size:24px;
font-weight:700;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:500;
}

.hero{
height:100vh;
background:linear-gradient(rgba(0,43,128,.75),rgba(214,40,40,.75)),
url('https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1500&q=80');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero-content h1{
font-size:55px;
margin-bottom:15px;
}

.hero-content p{
font-size:22px;
margin-bottom:20px;
}

.btn{
display:inline-block;
background:#ffcc00;
color:#000;
padding:12px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
margin-bottom:40px;
color:#002b80;
font-size:35px;
}

.about,.admission,.principal,.contact{
background:white;
border-radius:15px;
padding:40px;
box-shadow:0 4px 12px rgba(0,0,0,0.08);
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 4px 10px rgba(0,0,0,.08);
text-align:center;
}

.card h3{
color:#002b80;
margin-bottom:10px;
}

.contact form{
display:grid;
gap:15px;
}

input,textarea{
padding:12px;
border:1px solid #ccc;
border-radius:8px;
}

button{
background:#002b80;
color:white;
border:none;
padding:12px;
border-radius:8px;
cursor:pointer;
}

footer{
background:#002b80;
color:white;
text-align:center;
padding:20px;
}

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

@media(max-width:768px){
.hero-content h1{
font-size:34px;
}
nav ul{
display:none;
}
}
</style>
</head>

<body>

<nav>
<div class="logo">TPSS</div>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#admission">Admission</a></li>
<li><a href="#facilities">Facilities</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<div class="hero-content">
<img src="logo.png" width="120">
<h1>The Pioneer's School System</h1>
<p>Admissions Open 2026-2027</p>
<p>Play Group to Matric</p>
<a href="#contact" class="btn">Apply Now</a>
</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>
<div class="about">
<p>
Since 1977, The Pioneer's School System has been providing quality education,
academic excellence and character building in Faisalabad.
Our mission is to prepare confident, responsible and successful students.
</p>
</div>
</section>

<section id="facilities">
<h2 class="section-title">Our Facilities</h2>
<div class="cards">

<div class="card">
<h3>Qualified Teachers</h3>
<p>Experienced and dedicated teaching staff.</p>
</div>

<div class="card">
<h3>Science Education</h3>
<p>Strong focus on science and practical learning.</p>
</div>

<div class="card">
<h3>Computer Learning</h3>
<p>Modern computer education for students.</p>
</div>

<div class="card">
<h3>Co-Curricular Activities</h3>
<p>Sports, events and personality development.</p>
</div>

</div>
</section>

<section id="admission">
<h2 class="section-title">Admissions</h2>
<div class="admission">
<h3>Required Documents</h3>
<br>
<ul>
<li>B-Form / Birth Certificate</li>
<li>2 Passport Size Photographs</li>
<li>Previous Result Card</li>
<li>Parent CNIC Copy</li>
</ul>
</div>
</section>

<section>
<h2 class="section-title">Principal's Message</h2>
<div class="principal">
<h3>Mr. Ishtiaq Ahmad Gondal</h3>
<br>
<p>
We believe every child has the potential to succeed.
Our aim is to provide a positive environment where students
can grow academically and morally.
</p>
<br>
<p><strong>Management:</strong> Mrs. Naeema Ishtiaq</p>
</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>
<div class="contact">
<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Email Address">
<input type="text" placeholder="Phone Number">
<textarea rows="5" placeholder="Message"></textarea>
<button type="submit">Submit Inquiry</button>
</form>

<br>

<p><strong>Address:</strong><br>
479-B People's Colony No.1, Satyana Road, Faisalabad
</p>

<p><strong>Phone:</strong><br>
03061613136<br>
03007629136
</p>

<p><strong>Email:</strong><br>
thepioneerschoolsystem136@gmail.com
</p>

</div>
</section>

<footer>
© 2026 The Pioneer's School System | Since 1977
</footer>

<a class="whatsapp"
href="https://wa.me/923061613136">
WhatsApp
</a>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Pioneer's School System</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f7fb;
color:#333;
}

nav{
position:fixed;
top:0;
width:100%;
background:#002b80;
padding:15px 5%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
}

nav .logo{
color:#fff;
font-size:24px;
font-weight:700;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:500;
}

.hero{
height:100vh;
background:linear-gradient(rgba(0,43,128,.75),rgba(214,40,40,.75)),
url('https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1500&q=80');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

.hero-content h1{
font-size:55px;
margin-bottom:15px;
}

.hero-content p{
font-size:22px;
margin-bottom:20px;
}

.btn{
display:inline-block;
background:#ffcc00;
color:#000;
padding:12px 30px;
border-radius:30px;
text-decoration:none;
font-weight:600;
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
margin-bottom:40px;
color:#002b80;
font-size:35px;
}

.about,.admission,.principal,.contact{
background:white;
border-radius:15px;
padding:40px;
box-shadow:0 4px 12px rgba(0,0,0,0.08);
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 4px 10px rgba(0,0,0,.08);
text-align:center;
}

.card h3{
color:#002b80;
margin-bottom:10px;
}

.contact form{
display:grid;
gap:15px;
}

input,textarea{
padding:12px;
border:1px solid #ccc;
border-radius:8px;
}

button{
background:#002b80;
color:white;
border:none;
padding:12px;
border-radius:8px;
cursor:pointer;
}

footer{
background:#002b80;
color:white;
text-align:center;
padding:20px;
}

.whatsapp{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
}

@media(max-width:768px){
.hero-content h1{
font-size:34px;
}
nav ul{
display:none;
}
}
</style>
</head>

<body>

<nav>
<div class="logo">TPSS</div>
<ul>
<li><a href="#about">About</a></li>
<li><a href="#admission">Admission</a></li>
<li><a href="#facilities">Facilities</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<div class="hero-content">
<img src="logo.png" width="120">
<h1>The Pioneer's School System</h1>
<p>Admissions Open 2026-2027</p>
<p>Play Group to Matric</p>
<a href="#contact" class="btn">Apply Now</a>
</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>
<div class="about">
<p>
Since 1977, The Pioneer's School System has been providing quality education,
academic excellence and character building in Faisalabad.
Our mission is to prepare confident, responsible and successful students.
</p>
</div>
</section>

<section id="facilities">
<h2 class="section-title">Our Facilities</h2>
<div class="cards">

<div class="card">
<h3>Qualified Teachers</h3>
<p>Experienced and dedicated teaching staff.</p>
</div>

<div class="card">
<h3>Science Education</h3>
<p>Strong focus on science and practical learning.</p>
</div>

<div class="card">
<h3>Computer Learning</h3>
<p>Modern computer education for students.</p>
</div>

<div class="card">
<h3>Co-Curricular Activities</h3>
<p>Sports, events and personality development.</p>
</div>

</div>
</section>

<section id="admission">
<h2 class="section-title">Admissions</h2>
<div class="admission">
<h3>Required Documents</h3>
<br>
<ul>
<li>B-Form / Birth Certificate</li>
<li>2 Passport Size Photographs</li>
<li>Previous Result Card</li>
<li>Parent CNIC Copy</li>
</ul>
</div>
</section>

<section>
<h2 class="section-title">Principal's Message</h2>
<div class="principal">
<h3>Mr. Ishtiaq Ahmad Gondal</h3>
<br>
<p>
We believe every child has the potential to succeed.
Our aim is to provide a positive environment where students
can grow academically and morally.
</p>
<br>
<p><strong>Management:</strong> Mrs. Naeema Ishtiaq</p>
</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>
<div class="contact">
<form>
<input type="text" placeholder="Your Name">
<input type="email" placeholder="Email Address">
<input type="text" placeholder="Phone Number">
<textarea rows="5" placeholder="Message"></textarea>
<button type="submit">Submit Inquiry</button>
</form>

<br>

<p><strong>Address:</strong><br>
479-B People's Colony No.1, Satyana Road, Faisalabad
</p>

<p><strong>Phone:</strong><br>
03061613136<br>
03007629136
</p>

<p><strong>Email:</strong><br>
thepioneerschoolsystem136@gmail.com
</p>

</div>
</section>

<footer>
© 2026 The Pioneer's School System | Since 1977
</footer>

<a class="whatsapp"
href="https://wa.me/923061613136">
WhatsApp
</a>

</body>
</html>
