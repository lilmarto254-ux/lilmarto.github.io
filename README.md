<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Step &amp; Style | Shoes and Fashion Picks</title>
<meta name="description" content="Hand-picked shoes and fashion finds, curated on Pinterest. Shop the looks.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=DM+Sans:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#f4f2f7; --surface:#ffffff; --ink:#1d1b26; --muted:#6a6677;
  --accent:#e60023; --accent-ink:#ffffff; --line:#e2dfe9; --tag:#ebe7f3;
  --display:"Bricolage Grotesque","Helvetica Neue",Arial,sans-serif;
  --body:"DM Sans","Helvetica Neue",Arial,sans-serif;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#16141c; --surface:#201e29; --ink:#f1eff6; --muted:#a29eb2;
    --line:#332f40; --tag:#2b2837;
  }
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:var(--ink);font-family:var(--body);line-height:1.6;font-size:17px}
a{color:inherit}
:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.wrap{max-width:1100px;margin:0 auto;padding:0 20px}

header.top{display:flex;justify-content:space-between;align-items:center;padding:20px 0}
.logo{font-family:var(--display);font-weight:800;font-size:1.4rem;text-decoration:none;letter-spacing:-.02em}
nav a{margin-left:20px;text-decoration:none;color:var(--muted);font-weight:500}
nav a:hover{color:var(--ink)}

.hero{padding:56px 0 40px;max-width:760px}
.hero h1{font-family:var(--display);font-weight:800;font-size:clamp(2.6rem,8vw,5rem);line-height:.98;letter-spacing:-.035em;margin:0 0 20px}
.hero p{font-size:1.15rem;color:var(--muted);max-width:56ch;margin:0 0 28px}
.btn{display:inline-block;background:var(--accent);color:var(--accent-ink);font-weight:700;text-decoration:none;padding:13px 24px;border-radius:999px;border:0;cursor:pointer;font:inherit;font-weight:700}
.btn:hover{filter:brightness(.92)}
.btn.ghost{background:transparent;color:var(--ink);border:2px solid var(--line);margin-left:10px}

.filters{display:flex;flex-wrap:wrap;gap:10px;margin:36px 0 24px}
.filters button{font:inherit;font-weight:500;background:var(--tag);color:var(--ink);border:0;padding:9px 18px;border-radius:999px;cursor:pointer}
.filters button[aria-pressed="true"]{background:var(--ink);color:var(--bg)}

.grid{columns:3 260px;column-gap:20px}
.card{break-inside:avoid;background:var(--surface);border-radius:20px;overflow:hidden;margin:0 0 20px;border:1px solid var(--line)}
.card .pic{display:block;width:100%;aspect-ratio:var(--ratio,4/5);object-fit:cover;background:linear-gradient(135deg,var(--c1),var(--c2))}
.card .info{padding:16px 18px 20px}
.card h3{font-family:var(--display);font-size:1.15rem;margin:0 0 4px;letter-spacing:-.01em}
.card p{margin:0 0 14px;color:var(--muted);font-size:.95rem}
.card .row{display:flex;justify-content:space-between;align-items:center;gap:10px}
.price{font-weight:700}
.card .btn{padding:9px 18px;font-size:.95rem}

.about{display:grid;grid-template-columns:1fr 1fr;gap:40px;padding:64px 0;border-top:1px solid var(--line);margin-top:30px}
.about h2{font-family:var(--display);font-size:2rem;letter-spacing:-.02em;margin:0}
.about p{margin:0 0 14px;color:var(--muted)}
@media(max-width:700px){.about{grid-template-columns:1fr;gap:16px}.btn.ghost{margin:10px 0 0}}

.disclosure{background:var(--tag);border-radius:16px;padding:16px 20px;font-size:.92rem;color:var(--muted);margin-bottom:30px}
footer{padding:30px 0 50px;color:var(--muted);font-size:.9rem;border-top:1px solid var(--line)}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<div class="wrap">

  <header class="top">
    <a class="logo" href="#">Step &amp; Style</a>
    <nav>
      <a href="#shop">Shop</a>
      <a href="#about">About</a>
      <a href="https://www.pinterest.com/YOUR_USERNAME/" target="_blank" rel="noopener">Pinterest</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Shoes and outfits worth pinning.</h1>
    <p>I find the sneakers, boots, and everyday fashion pieces that look great and fit real budgets. Every pick links straight to the store.</p>
    <a class="btn" href="#shop">Shop the picks</a>
    <a class="btn ghost" href="https://www.pinterest.com/YOUR_USERNAME/" target="_blank" rel="noopener">Follow on Pinterest</a>
  </section>

  <section id="shop" aria-labelledby="shop-h">
    <h2 id="shop-h" style="font-family:var(--display);font-size:2rem;letter-spacing:-.02em;margin:40px 0 0">This week's picks</h2>
    <div class="filters" role="group" aria-label="Filter by category"></div>
    <div class="disclosure">Disclosure: Some links on this page are affiliate links. If you buy through them, I may earn a small commission at no extra cost to you.</div>
    <div class="grid" id="grid"></div>
  </section>

  <section class="about" id="about">
    <h2>About this page</h2>
    <div>
      <p>This is the home of my Pinterest boards. I pin new shoes and outfit ideas every week, and the best ones end up here with a direct link to buy.</p>
      <p>Want to see more? Follow the boards and save anything you like.</p>
      <a class="btn" href="https://www.pinterest.com/YOUR_USERNAME/" target="_blank" rel="noopener">See all boards</a>
    </div>
  </section>

  <footer>
    <p>&copy; <span id="yr"></span> Step &amp; Style. As an affiliate, I earn from qualifying purchases.</p>
  </footer>
</div>

<script>
/* ============ EDIT THIS LIST ============
   title, note, price, category, link (your affiliate link),
   img (product image URL, or "" for a color block),
   ratio (image shape, e.g. "4/5", "1/1", "3/4"), c1/c2 (fallback colors)
======================================== */
const products = [
  {title:"White Leather Sneakers", note:"Clean, goes with everything.", price:"$59", category:"Sneakers", link:"https://example.com/your-affiliate-link-1", img:"", ratio:"4/5", c1:"#d9d4e8", c2:"#f3f0fa"},
  {title:"Chunky Platform Boots", note:"Wear them with dresses or jeans.", price:"$84", category:"Boots", link:"https://example.com/your-affiliate-link-2", img:"", ratio:"1/1", c1:"#2b2837", c2:"#5a5470"},
  {title:"Oversized Denim Jacket", note:"A layer for every season.", price:"$48", category:"Outfits", link:"https://example.com/your-affiliate-link-3", img:"", ratio:"3/4", c1:"#8fb0d8", c2:"#c9dcf2"},
  {title:"Strappy Block Heels", note:"Comfortable enough for all day.", price:"$39", category:"Heels", link:"https://example.com/your-affiliate-link-4", img:"", ratio:"1/1", c1:"#f2b8c0", c2:"#fbe1e4"},
  {title:"Retro Running Shoes", note:"Soft sole, bold colors.", price:"$72", category:"Sneakers", link:"https://example.com/your-affiliate-link-5", img:"", ratio:"4/5", c1:"#ffb36b", c2:"#ffe0bf"},
  {title:"Linen Co-ord Set", note:"Matching top and trousers.", price:"$55", category:"Outfits", link:"https://example.com/your-affiliate-link-6", img:"", ratio:"3/4", c1:"#b8d4b0", c2:"#e3f0df"},
  {title:"Leather Ankle Boots", note:"Smart casual, built to last.", price:"$95", category:"Boots", link:"https://example.com/your-affiliate-link-7", img:"", ratio:"4/5", c1:"#6b4a3a", c2:"#a07a64"}
];

const grid = document.getElementById("grid");
const filters = document.querySelector(".filters");
const cats = ["All", ...new Set(products.map(p => p.category))];
let active = "All";

function esc(s){return String(s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]))}

function render(){
  grid.innerHTML = products.filter(p => active==="All" || p.category===active).map(p => `
    <article class="card">
      ${p.img
        ? `<img class="pic" style="--ratio:${esc(p.ratio)}" src="${esc(p.img)}" alt="${esc(p.title)}" loading="lazy">`
        : `<div class="pic" role="img" aria-label="${esc(p.title)}" style="--ratio:${esc(p.ratio)};--c1:${esc(p.c1)};--c2:${esc(p.c2)}"></div>`}
      <div class="info">
        <h3>${esc(p.title)}</h3>
        <p>${esc(p.note)}</p>
        <div class="row">
          <span class="price">${esc(p.price)}</span>
          <a class="btn" href="${esc(p.link)}" target="_blank" rel="sponsored noopener">Shop now</a>
        </div>
      </div>
    </article>`).join("");
}

filters.innerHTML = cats.map(c => `<button type="button" aria-pressed="${c===active}">${c}</button>`).join("");
filters.addEventListener("click", e => {
  const b = e.target.closest("button"); if(!b) return;
  active = b.textContent;
  filters.querySelectorAll("button").forEach(x => x.setAttribute("aria-pressed", x===b));
  render();
});

render();
document.getElementById("yr").textContent = new Date().getFullYear();
</script>
</body>
</html>
