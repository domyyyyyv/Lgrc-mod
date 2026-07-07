<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Langley Rod & Gun Club</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Inter,sans-serif;
    background:#eef2f5;
    color:#222;
}

header{
    background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
    url("https://images.unsplash.com/photo-1511884642898-4c92249e20b6?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    height:75vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
}

.hero{
    max-width:800px;
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.hero p{
    font-size:22px;
    margin-bottom:35px;
}

.buttons{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

.button{
    background:#1f7a43;
    color:white;
    padding:16px 30px;
    border-radius:10px;
    text-decoration:none;
    font-weight:700;
    transition:.3s;
}

.button:hover{
    background:#14592f;
}

.button.secondary{
    background:white;
    color:#123b63;
}

.status{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    max-width:1200px;
    margin:-45px auto 50px;
    padding:0 20px;
}

.card{
    background:white;
    border-radius:16px;
    padding:25px;
    box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.card h3{
    margin-bottom:10px;
}

.section{
    max-width:1200px;
    margin:auto;
    padding:40px 20px;
}

.section h2{
    font-size:38px;
    margin-bottom:25px;
    color:#123b63;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

.feature{
    background:white;
    border-radius:15px;
    padding:30px;
    transition:.25s;
    box-shadow:0 5px 18px rgba(0,0,0,.08);
}

.feature:hover{
    transform:translateY(-6px);
}

.feature h3{
    margin-bottom:15px;
}

.schedule{
    width:100%;
    border-collapse:collapse;
    background:white;
    border-radius:15px;
    overflow:hidden;
}

.schedule th{
    background:#123b63;
    color:white;
    padding:18px;
}

.schedule td{
    padding:16px;
    border-bottom:1px solid #eee;
    text-align:center;
}

footer{
    background:#123b63;
    color:white;
    text-align:center;
    padding:50px 20px;
    margin-top:60px;
}
</style>
</head>

<body>

<header>
<div class="hero">
<h1>Langley Rod & Gun Club</h1>

<p>Trap • Skeet • Indoor Range • Archery • Junior Programs</p>

<div class="buttons">
<a href="#" class="button">Become a Member</a>
<a href="#" class="button secondary">View Calendar</a>
</div>
</div>
</header>

<section class="status">

<div class="card">
<h3>🟢 Indoor Range</h3>
<p>Open Today</p>
</div>

<div class="card">
<h3>🟢 Outdoor Ranges</h3>
<p>Summer Hours</p>
</div>

<div class="card">
<h3>🎯 5-Stand</h3>
<p>Wednesday 4:30–7:30 PM</p>
</div>

<div class="card">
<h3>📅 Next Meeting</h3>
<p>July 8 • 7:00 PM</p>
</div>

</section>

<section class="section">

<h2>Explore the Club</h2>

<div class="grid">

<div class="feature">
<h3>🎯 Indoor Range</h3>
<p>Pistol, rifle and junior shooting sessions with certified range officers.</p>
</div>

<div class="feature">
<h3>🏹 Archery</h3>
<p>Outdoor range, beginner courses, Junior Olympian program and leagues.</p>
</div>

<div class="feature">
<h3>💥 Trap & Skeet</h3>
<p>Competitive and recreational shotgun shooting throughout the year.</p>
</div>

<div class="feature">
<h3>👨‍👩‍👧 Membership</h3>
<p>Join online in minutes and enjoy all club facilities and events.</p>
</div>

</div>

</section>

<section class="section">

<h2>This Week</h2>

<table class="schedule">

<tr>
<th>Day</th>
<th>Events</th>
</tr>

<tr>
<td>Monday</td>
<td>Indoor Range</td>
</tr>

<tr>
<td>Tuesday</td>
<td>Junior Archery • Drop-In Archery</td>
</tr>

<tr>
<td>Wednesday</td>
<td>Indoor Range • 5-Stand • General Meeting</td>
</tr>

<tr>
<td>Thursday</td>
<td>Junior Rifle</td>
</tr>

<tr>
<td>Friday</td>
<td>Trap & Skeet</td>
</tr>

<tr>
<td>Saturday</td>
<td>Indoor Range • Outdoor Ranges</td>
</tr>

<tr>
<td>Sunday</td>
<td>Archery • Outdoor Ranges</td>
</tr>

</table>

</section>

<footer>

<h2>Langley Rod & Gun Club</h2>

<p>Safe • Professional • Family Friendly</p>

<p style="margin-top:15px;">
© 2026 Langley Rod & Gun Club
</p>

</footer>

</body>
</html
