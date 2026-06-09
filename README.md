<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>InAmigos Foundation</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif}
body{background:#f4f4f4;color:#333;line-height:1.6}
nav{background:#0d3b66;color:#fff;padding:15px 30px;position:sticky;top:0}
nav h2{text-align:center}
.hero{height:70vh;display:flex;align-items:center;justify-content:center;text-align:center;color:#fff;
background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),url('https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=1400&q=80') center/cover}
.hero h1{font-size:3rem}
section{padding:60px 10%}
h2{text-align:center;color:#0d3b66;margin-bottom:25px}
.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
.card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 4px 12px rgba(0,0,0,.15);transition:.3s}
.card:hover{transform:translateY(-8px)}
.card img{width:100%;height:220px;object-fit:cover}
.card h3{padding:15px;color:#0d3b66}
.card p{padding:0 15px 20px}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:20px}
.stat{background:#0d3b66;color:#fff;padding:25px;border-radius:10px;text-align:center}
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:15px}
.gallery img{width:100%;height:220px;object-fit:cover;border-radius:10px}
form{max-width:600px;margin:auto;display:flex;flex-direction:column;gap:12px}
input,textarea,button{padding:12px}
button{background:#28a745;color:#fff;border:none;cursor:pointer}
footer{background:#0d3b66;color:#fff;text-align:center;padding:20px}
</style>
</head>
<body>
<nav><h2>InAmigos Foundation</h2></nav>

<div class="hero">
<div>
<h1>Creating Impact, Changing Lives</h1>
<p>Together for Education, Environment, Welfare & Youth Development</p>
</div>
</div>

<section>
<h2>About InAmigos Foundation</h2>
<p>About InAmigos Foundation

InAmigos Foundation is a youth-driven non-profit organization dedicated to creating positive social change through education, community welfare, environmental sustainability, women empowerment, animal welfare, and skill development initiatives. Founded in 2020, the organization aims to bridge social gaps by encouraging volunteerism, innovation, and collective action.

The foundation works through various impactful projects such as Project SEVA (community welfare), Project BACHPANSHALA (education for underprivileged children), Project UDAAN (women empowerment), Project PRAKRITI (environmental conservation), Project JEEV (animal welfare), and Project VIKAS (skill development and internships).

With the support of dedicated volunteers, interns, and community members across India, InAmigos Foundation strives to build a more inclusive, sustainable, and empowered society where every individual has the opportunity to grow and contribute meaningfully.

Mission: To inspire and empower communities through sustainable social initiatives and volunteer-driven action.

Vision: To create a society where education, equality, opportunity, and compassion are accessible to everyone.</p>
</section>

<section>
<h2>Flagship Projects</h2>
<div class="projects">

<div class="card">
<img src="https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=800&q=80">
<h3>📚 BachpanShala</h3>
<p>Education, digital literacy and mentorship programs for underprivileged children.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?auto=format&fit=crop&w=800&q=80">
<h3>👩 Udaan</h3>
<p>Women empowerment through skill development, entrepreneurship and awareness programs.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=800&q=80">
<h3>❤️ Seva</h3>
<p>Food drives, clothing donations, blood donation camps and welfare activities.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1548199973-03cce0bbc87b?auto=format&fit=crop&w=800&q=80">
<h3>🐾 Jeev</h3>
<p>Animal welfare initiative supporting stray and abandoned animals.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1466611653911-95081537e5b7?auto=format&fit=crop&w=800&q=80">
<h3>🌱 Prakriti</h3>
<p>Tree plantation and environmental awareness campaigns.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=800&q=80">
<h3>💻 Vikas</h3>
<p>Internship and skill development opportunities for students and youth.</p>
</div>

</div>
</section>

<section>
<h2>Impact</h2>
<div class="stats">
<div class="stat"><h3>50,000+</h3><p>Beneficiaries</p></div>
<div class="stat"><h3>20,000+</h3><p>Trees Planted</p></div>
<div class="stat"><h3>30,000+</h3><p>Interns Trained</p></div>
<div class="stat"><h3>200+</h3><p>Volunteers</p></div>
</div>
</section>

<section>
<h2>Gallery</h2>
<div class="gallery">
<img src="https://images.unsplash.com/photo-1469571486292-b53601020f36?auto=format&fit=crop&w=800&q=80">
<img src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846?auto=format&fit=crop&w=800&q=80">
<img src="https://images.unsplash.com/photo-1529390079861-591de354faf5?auto=format&fit=crop&w=800&q=80">
<img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=800&q=80">
</div>
</section>

<section>
<h2>Become a Volunteer</h2>
<form onsubmit="event.preventDefault();alert('Thank you for volunteering!');">
<input type="text" placeholder="Full Name" required>
<input type="email" placeholder="Email Address" required>
<textarea placeholder="Why do you want to volunteer?" required></textarea>
<button type="submit">Submit</button>
</form>
</section>

<footer>© 2026 InAmigos Foundation</footer>
</body>
</html>
