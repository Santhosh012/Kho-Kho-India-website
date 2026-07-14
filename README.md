# Kho-Kho-India-website
This website is linked to youtube channel, which is exploring the sports side especially the game kho kho
<!DOCTYPE html><html><head><meta charset='UTF-8'><meta name='viewport' content='width=device-width,initial-scale=1'><title>KhoKhoIndia</title><link rel='stylesheet' href='style.css'></head><body>
<div id='loader'><div class='spin'></div><h1>KhoKhoIndia</h1></div>
<header class='hero'><img src='assets/hero.png'><div><h1>KhoKhoIndia</h1><p>Explore • Inspire • Create</p><a class='btn' href='https://youtube.com/@khokhoindia?si=nMv70IOR6jXQT-JR'>Subscribe</a></div></header>
<section><h2>About</h2><p>Welcome to KhoKhoIndia.</p></section>
<section><h2>Latest Videos</h2><iframe width='560' height='315' src='https://www.youtube.com/embed?listType=user_uploads&list=khokhoindia'></iframe></section>
<script src='script.js'></script></body></html>
window.onload=()=>setTimeout(()=>document.getElementById('loader').style.display='none',1800);
body{margin:0;background:#111;color:#fff;font-family:Arial}#loader{position:fixed;inset:0;background:#000;display:flex;flex-direction:column;justify-content:center;align-items:center;z-index:9}.spin{width:70px;height:70px;border:6px solid #444;border-top:6px solid red;border-radius:50%;animation:s 1s linear infinite}@keyframes s{to{transform:rotate(360deg)}}.hero{display:flex;flex-wrap:wrap;gap:20px;align-items:center;justify-content:center;padding:60px}.hero img{max-width:320px;border-radius:20px}.btn{background:red;color:#fff;padding:12px 20px;text-decoration:none;border-radius:8px}section{padding:30px}
