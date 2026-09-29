<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Panji Cahya Prasetyo — Grimoire</title>
<link href="https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&family=Crimson+Pro:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#0a0908;--page:#14110e;--ink:#eee6d2;--mute:#a59d8a;--gold:#d4af37;--red:#8b0000;--green:#2e8b57;--line:#3a3222;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#0a0908}}
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--ink);font-family:"Crimson Pro",Georgia,serif;font-size:19px;line-height:1.65}
.wrap{max-width:860px;margin:0 auto;padding:32px 20px 64px}
.book{background:var(--page);border:2px solid var(--gold);border-radius:6px;padding:40px 32px;box-shadow:0 0 0 6px var(--bg),0 0 0 8px var(--red)}
h1,h2{font-family:"UnifrakturCook","Old English Text MT",Georgia,serif;font-weight:700;margin:0;color:var(--gold)}
h1{font-size:clamp(2.4rem,8vw,4.4rem);line-height:1.05}
h2{font-size:1.9rem;margin:48px 0 14px;padding-bottom:6px;border-bottom:1px solid var(--line)}
.tag{color:var(--mute);margin:10px 0 0}
.quote{border-left:3px solid var(--red);padding:2px 0 2px 16px;margin:22px 0;font-style:italic}
.clover{color:var(--green);font-size:1.4rem}
.skills{display:grid;grid-template-columns:repeat(auto-fill,minmax(240px,1fr));gap:12px}
.skill{border:1px solid var(--line);padding:10px 14px;border-radius:3px}
.skill b{display:block}
.bar{height:6px;background:var(--line);margin-top:8px;border-radius:3px;overflow:hidden}
.bar i{display:block;height:100%;background:var(--green)}
.bar i.m{background:var(--green)}
.chips{display:flex;flex-wrap:wrap;gap:8px;padding:0;list-style:none;margin:12px 0}
.chips li{border:1px solid var(--gold);color:var(--gold);padding:2px 12px;border-radius:999px;font-size:.95rem}
.project{border:1px solid var(--gold);border-left:5px solid var(--red);padding:20px 22px;border-radius:3px}
.project h3{margin:0 0 6px;font-size:1.4rem}
.project ul{margin:10px 0;padding-left:20px}
pre{background:#000;border:1px solid var(--line);padding:14px;overflow-x:auto;color:var(--green);font-size:.9rem;border-radius:3px}
table{width:100%;border-collapse:collapse}
td,th{text-align:left;padding:8px 10px;border-bottom:1px solid var(--line)}
th{color:var(--gold);font-weight:600}
.wide{overflow-x:auto}
.pal{display:flex;gap:8px;margin-top:8px}
.pal span{width:44px;height:44px;border:1px solid var(--line);border-radius:3px}
footer{text-align:center;margin-top:48px;color:var(--mute)}
footer b{color:var(--gold);font-family:"UnifrakturCook",Georgia,serif;font-size:1.5rem;font-weight:700}
a{color:var(--gold)}
:focus-visible{outline:2px solid var(--gold);outline-offset:2px}
</style>
</head>
<body>
<div class="wrap"><div class="book">

<header>
<div class="clover" aria-hidden="true">☘</div>
<h1>Panji Cahya Prasetyo</h1>
<blockquote class="quote">"If you don't give up, you will succeed."</blockquote>
<p>Selamat datang di Grimoire pribadi saya. Saya Panji, mahasiswa Informatika yang sedang mengembangkan kemampuan di bidang pemrograman, web development, database, dan backend.</p>
<p>Kemampuan tidak terbentuk secara instan. Setiap project, error, debugging, dan commit adalah bagian dari perjalanan menjadi developer yang lebih baik.</p>
</header>

<h2>skill yang Dikuasai</h2>
<div class="skills">
<div class="skill"><b>HTML</b>Pemula<div class="bar"><i class="m" style="width:30%"></i></div></div>
<div class="skill"><b>CSS</b>Pemula<div class="bar"><i class="m" style="width:30%"></i></div></div>
<div class="skill"><b>MySQL / MariaDB</b>Pemula<div class="bar"><i class="m" style="width:30%"></i></div></div>
<div class="skill"><b>JavaScript</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
<div class="skill"><b>TypeScript</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
<div class="skill"><b>PHP</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
<div class="skill"><b>Node.js / Express</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
<div class="skill"><b>Svelte</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
<div class="skill"><b>Git &amp; GitHub</b>Pemula<div class="bar"><i style="width:30%"></i></div></div>
</div>
<p>Sedang dipelajari:</p>
<ul class="chips"><li>Backend Development</li><li>REST API</li><li>Database Management</li><li>Flutter</li><li>TypeScript</li><li>Fullstack Web</li></ul>

<h2>Project</h2>
<div class="project">
<h3>Tabulampot Tracker</h3>
<p>Aplikasi untuk memantau dan mengelola perawatan tanaman buah dalam pot.</p>
<ul>
<li>Register dan login dengan JWT</li>
<li>CRUD tanaman</li>
<li>Catatan penyiraman dan pemupukan</li>
<li>Jadwal perawatan</li>
<li>Dashboard monitoring</li>
</ul>
<ul class="chips"><li>TypeScript</li><li>Express.js</li><li>Drizzle ORM</li><li>MariaDB</li><li>JWT</li></ul>
</div>

<h2>Bukri Commit</h2>
<pre>$ git log --oneline -5

feat(p1): biodata + profile
style(p1): black clover theme
docs(p1): init My Profile</pre>

<h2>Pendidikan</h2>
<div class="wide"><table>
<tr><th>Tahun</th><th>Institusi</th><th>Program</th></tr>
<tr><td>2024 – sekarang</td><td>Universitas Madura (UNIRA)</td><td>Informatika</td></tr>
<tr><td>2021 – 2024</td><td>SMA NEGERI 2 PAMEKASAN</td><td>IPA</td></tr>
<tr><td>2018 – 2021</td><td>SMP NEGERI 2 PAMEKASAN</td><td>-</td></tr>
<tr><td>2012 – 2018</td><td>SD NEGERI 2 PANGLEGUR</td><td>-</td></tr>
</table></div>

<h2>Profil Karakter</h2>
<div class="wide"><table>
<tr><th>Nama</th><td>Panji Cahya Prasetyo</td></tr>
<tr><th>Panggilan</th><td>Panji</td></tr>
<tr><th>NIM</th><td>2024520074</td></tr>
<tr><th>Lokasi</th><td>Pamekasan, Jawa Timur</td></tr>
<tr><th>Status</th><td>Mahasiswa Informatika</td></tr>
</table></div>

<h2>Tekad</h2>
<blockquote class="quote">"My strength is never giving up.!"</blockquote>
<p>Saya masih belajar dan terus meningkatkan kemampuan lewat project, tugas, organisasi, dan pengalaman baru. Motto saya: <i>surpass your limits.</i></p>
<div class="pal" aria-label="Palet warna tema"><span style="background:#000"></span><span style="background:#d4af37"></span><span style="background:#8b0000"></span><span style="background:#2e8b57"></span></div>

<h2>Tautan</h2>
<ul>
<li>My Profile: segera hadir</li>
<li>Video P1: segera hadir</li>
<li><a href="https://github.com/">GitHub Panji Cahya Prasetyo</a></li>
</ul>

<footer>
<b>Panji Cahya Prasetyo</b>
<div>P1 — Pemrograman Platform</div>
</footer>

</div></div>
</body>
</html>
