o# Urban-Escorts-Uganda
We offer the best options in kampala and arpund kampala
<!DOCTYPE html>
<html>

<head>

<title>Urban Platform Uganda</title>

<link href="https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap" rel="stylesheet">

<style>

body{
margin:0;
font-family:Arial;
background:linear-gradient(135deg,#ff4e50,#f9d423);
color:white;
}

header{
background:black;
padding:15px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
font-size:18px;
}

nav a:hover{
color:gold;
}

.marquee{
font-family:'UnifrakturCook',cursive;
font-size:28px;
background:black;
color:gold;
padding:10px;
}

.page{
display:none;
padding:40px;
text-align:center;
}

.active{
display:block;
}

.card{
background:rgba(0,0,0,0.6);
padding:20px;
margin:20px auto;
border-radius:10px;
max-width:400px;
}

input,textarea{
width:80%;
padding:10px;
margin:8px;
border-radius:6px;
border:none;
}

button{
background:gold;
border:none;
padding:10px 20px;
font-weight:bold;
cursor:pointer;
}

.gallery img{
width:200px;
margin:10px;
border-radius:10px;
}

footer{
background:black;
padding:20px;
text-align:center;
margin-top:40px;
}

</style>

<script>

function showPage(page){
let pages=document.querySelectorAll(".page")
pages.forEach(p=>p.classList.remove("active"))

document.getElementById(page).classList.add("active")
}

function addComment(){
let name=document.getElementById("cname").value
let text=document.getElementById("ctext").value

let box=document.getElementById("comments")

let comment=document.createElement("p")

comment.innerHTML="<b>"+name+":</b> "+text

box.appendChild(comment)
}

</script>

</head>

<body>

<header>

<h1>URBAN PLATFORM UGANDA</h1>

<nav>

<a href="#" onclick="showPage('home')">Home</a>
<a href="#" onclick="showPage('profiles')">Profiles</a>
<a href="#" onclick="showPage('gallery')">Gallery</a>
<a href="#" onclick="showPage('signup')">Sign Up</a>
<a href="#" onclick="showPage('comments')">Comments</a>

</nav>

</header>

<div class="marquee">

<marquee>
WELCOME — WE NEED PARTICIPANTS FOR PAYMENTS
</marquee>

</div>

<!-- HOME -->

<section id="home" class="page active">

<h2>Welcome</h2>

<p>
This is a community platform where users can create accounts,
upload profiles and interact.
</p>

<p>Email: urbanescortsug.com</p>

<p>
TikTok:
<a href="https://tiktok.com/@urbanescortsuganda">
urban escorts uganda@tiktok.com
</a>
</p>

<p>
Mobile Money:
<b>+256 757848889</b>
</p>

</section>

<!-- PROFILES -->

<section id="profiles" class="page">

<h2>Profiles</h2>

<div class="card">

<img src="https://via.placeholder.com/200">

<h3>Name</h3>

<p>Age: 22</p>

<p>Location: Kampala</p>

<p>Bio: Add information about the user.</p>

</div>

<div class="card">

<img src="https://via.placeholder.com/200">

<h3>Name</h3>

<p>Age: 24</p>

<p>Location: Entebbe</p>

<p>Bio: Add profile description here.</p>

</div>

</section>

<!-- GALLERY -->

<section id="gallery" class="page">

<h2>Gallery</h2>

<div class="gallery">

<img src="https://via.placeholder.com/200">

<img src="https://via.placeholder.com/200">

<img src="https://via.placeholder.com/200">

</div>

</section>

<!-- SIGN UP -->

<section id="signup" class="page">

<h2>Create Account</h2>

<form>

<input type="text" placeholder="Full Name"><br>

<input type="number" placeholder="Age (18+ only)" min="18"><br>

<input type="text" placeholder="Location"><br>

<input type="file"><br>

<textarea placeholder="Bio / Preferences"></textarea><br>

<button>Create Account</button>

</form>

</section>

<!-- COMMENTS -->

<section id="comments" class="page">

<h2>Comment Section</h2>

<input id="cname" placeholder="Your name"><br>

<textarea id="ctext" placeholder="Your comment"></textarea><br>

<button onclick="addComment()">Post Comment</button>

<div id="comments"></div>

</section>

<footer>

<p>© 2026 Urban Platform Uganda</p>

</footer>

</body>

</html>
