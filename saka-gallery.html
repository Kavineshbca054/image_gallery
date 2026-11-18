<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>SAKA – Eternal Photo Gallery</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
<style>
:root{color-scheme:dark;--bg:#12020a;--bg2:#2a0817;--gold:#d4af37;--gold2:#ffd700;--cream:#f3e5ab;--muted:#a8a29e;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;min-height:100vh;color:#fff;font-family:'Montserrat',system-ui,sans-serif;background:linear-gradient(135deg,var(--bg),var(--bg2),var(--bg));overflow-x:hidden}
button{font:inherit;color:inherit;cursor:pointer}
.cz{font-family:'Cinzel',Georgia,serif}
.hidden{display:none!important}
#fx{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:0}
.logo{background:linear-gradient(135deg,#ffd700,#fff0a5,#d4af37,#fff,#ffd700);background-size:300% 300%;-webkit-background-clip:text;background-clip:text;-webkit-text-fill-color:transparent;animation:shine 5s linear infinite,glow 2.5s ease-in-out infinite alternate}
@keyframes shine{0%,100%{background-position:0 50%}50%{background-position:100% 50%}}
@keyframes glow{from{filter:drop-shadow(0 0 12px rgba(212,175,55,.3))}to{filter:drop-shadow(0 0 30px rgba(255,215,0,.7))}}
.wrap{position:relative;z-index:1}
#home{min-height:100vh;display:flex;flex-direction:column;justify-content:space-between;align-items:center;padding:48px 16px 24px;text-align:center}
.pill{display:inline-block;padding:4px 16px;border:1px solid rgba(212,175,55,.4);background:rgba(212,175,55,.1);border-radius:99px;color:var(--cream);font-size:12px;letter-spacing:.3em;text-transform:uppercase}
h1{font-size:clamp(56px,14vw,112px);letter-spacing:.25em;margin:10px 0 0;font-weight:900;line-height:1}
.sub{color:var(--cream);letter-spacing:.3em;font-size:14px;margin:6px 0}
.rule{width:128px;height:1px;background:linear-gradient(90deg,transparent,var(--gold),transparent);margin:16px auto}
.albums{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px;width:100%;max-width:1100px;margin:32px 0}
.album{position:relative;height:340px;border-radius:16px;overflow:hidden;border:2px solid rgba(212,175,55,.6);text-align:left;padding:0;background:linear-gradient(160deg,#4a0f2a,#1a0610);transition:transform .5s cubic-bezier(.175,.885,.32,1.275),box-shadow .5s}
.album:hover{transform:translateY(-10px) scale(1.03);box-shadow:0 20px 40px rgba(212,175,55,.35)}
.album img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;transition:transform .7s}
.album:hover img{transform:scale(1.1)}
.album .shade{position:absolute;inset:0;background:linear-gradient(to top,var(--bg),rgba(18,2,10,.4) 55%,transparent);opacity:.85}
.album .txt{position:absolute;left:0;right:0;bottom:0;padding:24px}
.tag{font-size:11px;letter-spacing:.2em;text-transform:uppercase;color:var(--gold2);font-weight:600}
.album h3{font-size:30px;margin:4px 0;font-weight:700}
.album small{color:#d1d5db;font-weight:300}
.go{margin-top:14px;color:var(--gold);font-size:12px;font-weight:600;letter-spacing:.1em}
footer{font-size:11px;letter-spacing:.2em;text-transform:uppercase;color:rgba(212,175,55,.7)}
#gallery{min-height:100vh;padding-bottom:64px}
.bar{position:sticky;top:env(safe-area-inset-top,0px);z-index:30;background:rgba(26,6,16,.8);backdrop-filter:blur(16px);border-bottom:1px solid rgba(212,175,55,.3);padding:14px 20px}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:rgba(26,6,16,.9);z-index:31}
.bar .in{max-width:1200px;margin:auto;display:flex;flex-wrap:wrap;gap:12px;align-items:center;justify-content:space-between}
.logo.s{font-size:28px;font-weight:900;letter-spacing:.15em;background-color:transparent;border:0;padding:0}
.tabs{display:flex;background:rgba(18,2,10,.8);border:1px solid rgba(212,175,55,.3);border-radius:12px;padding:4px;font-size:12px}
.tabs button{border:0;background:none;padding:6px 12px;border-radius:8px;color:#d1d5db}
.tabs button.on{background:var(--gold);color:var(--bg);font-weight:700}
.btn{padding:8px 16px;border-radius:12px;border:1px solid var(--gold);background:none;color:var(--gold2);font-size:12px;font-weight:600;letter-spacing:.08em;text-transform:uppercase}
.btn:hover{background:var(--gold);color:var(--bg)}
.main{max-width:1200px;margin:auto;padding:32px 20px 0}
.panel{background:rgba(26,6,16,.75);backdrop-filter:blur(16px);border:2px solid rgba(212,175,55,.45);border-radius:16px;padding:24px;max-width:720px;margin:0 auto 36px;text-align:center}
.panel h2{margin:0 0 14px;color:var(--cream);font-size:22px}
.panel form{display:flex;flex-wrap:wrap;gap:10px;justify-content:center}
.file{flex:1;min-width:200px;padding:12px;border:1px dashed rgba(212,175,55,.6);border-radius:12px;background:rgba(18,2,10,.6);color:#d1d5db;font-size:12px;cursor:pointer}
.file input{display:none}
select{padding:12px;border-radius:12px;background:var(--bg);border:1px solid rgba(212,175,55,.5);color:var(--cream);font:inherit;font-size:12px}
.go2{padding:12px 24px;border:0;border-radius:12px;background:linear-gradient(90deg,var(--gold),#aa8321);color:var(--bg);font-weight:700;font-size:12px;letter-spacing:.08em;text-transform:uppercase}
.go2:disabled{opacity:.5}
.note{color:var(--muted);font-size:12px;margin:8px 0 0}
.head{display:flex;justify-content:space-between;align-items:baseline;border-bottom:1px solid rgba(212,175,55,.2);padding-bottom:14px;margin-bottom:24px}
.head h3{margin:0;font-size:24px;color:var(--cream)}
.head p{margin:0;font-size:12px;color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(170px,1fr));gap:18px}
.ph{position:relative;aspect-ratio:1;border-radius:16px;overflow:hidden;border:2px solid rgba(212,175,55,.6);padding:0;background:var(--bg);transition:transform .4s,box-shadow .4s}
.ph:hover{transform:translateY(-6px) scale(1.02);box-shadow:0 12px 30px rgba(212,175,55,.3)}
.ph img{width:100%;height:100%;object-fit:cover}
.ph .ov{position:absolute;inset:0;display:flex;flex-direction:column;justify-content:flex-end;padding:10px;text-align:left;background:linear-gradient(to top,var(--bg),transparent 60%);opacity:0;transition:opacity .3s}
.ph:hover .ov{opacity:.95}
.ov span{font-size:10px;color:var(--gold2);font-weight:700;text-transform:uppercase}
.ov p{margin:0;font-size:12px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.empty{text-align:center;padding:48px 20px;max-width:420px;margin:24px auto;background:rgba(26,6,16,.75);border:1px solid rgba(212,175,55,.25);border-radius:16px;color:var(--muted);font-size:13px}
#toasts{position:fixed;top:calc(env(safe-area-inset-top,0px) + 16px);right:16px;z-index:60;display:flex;flex-direction:column;gap:8px;pointer-events:none}
.toast{background:rgba(26,6,16,.95);border:2px solid rgba(212,175,55,.6);padding:12px 16px;border-radius:12px;font-size:13px;box-shadow:0 8px 24px rgba(0,0,0,.5)}
#bell{position:fixed;right:16px;bottom:calc(env(safe-area-inset-bottom,0px) + 16px);z-index:55;width:52px;height:52px;border-radius:50%;border:2px solid var(--gold);background:rgba(26,6,16,.9);font-size:22px}
#bell b{position:absolute;top:-6px;right:-6px;min-width:22px;height:22px;border-radius:11px;background:#ff4d6d;font-size:12px;line-height:22px;text-align:center}
#lb{position:fixed;inset:0;z-index:70;background:rgba(0,0,0,.95);display:flex;flex-direction:column;align-items:center;justify-content:center;padding:16px}
#lb img{max-width:100%;max-height:78vh;border-radius:12px;border:2px solid rgba(212,175,55,.6);object-fit:contain}
#lb .x,#lb .n{position:absolute;width:46px;height:46px;border-radius:50%;border:1px solid rgba(255,255,255,.15);background:rgba(0,0,0,.5);font-size:22px}
#lb .x{top:calc(env(safe-area-inset-top,0px) + 14px);right:14px}
#lb .p{left:10px;top:50%}#lb .q{right:10px;top:50%}
#lbc{margin-top:14px;text-align:center;font-size:13px;color:#d1d5db}
#lbd{margin-top:12px;padding:8px 18px;border-radius:12px;border:1px solid #ff4d6d;background:none;color:#ff8fa3;font-size:12px;font-weight:600}
#lbd:hover{background:#ff4d6d;color:#fff}
#lock{position:fixed;inset:0;z-index:100;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#12020a,#2a0817,#12020a);text-align:center;padding:24px}
#lock form{display:flex;gap:10px;justify-content:center;margin-top:16px;flex-wrap:wrap}
#lkIn{padding:12px 16px;width:160px;text-align:center;letter-spacing:.4em;border-radius:12px;border:1px solid rgba(212,175,55,.6);background:#12020a;color:var(--cream);font:inherit;font-size:18px}
</style>
</head>
<body>
<canvas id="fx"></canvas>
<div id="toasts"></div>
<button id="bell" class="hidden" title="New photos" aria-label="New photos">🔔<b id="badge" class="hidden">0</b></button>

<div class="wrap">
<main id="home">
  <header>
    <div class="pill">Our Photo Gallery</div>
    <h1 class="logo cz">SAKA</h1>
    <p class="sub cz">OUR ETERNAL LOVE STORY</p>
    <div class="rule"></div>
    <p style="color:#e2c974;font-size:13px;letter-spacing:.2em;text-transform:uppercase;font-weight:300">Select an album to explore</p>
  </header>
  <section class="albums" id="albums"></section>
  <footer>© SAKA Memories • Forever &amp; Always</footer>
</main>

<div id="gallery" class="hidden">
  <header class="bar"><div class="in">
    <button class="logo s cz" id="toHome">SAKA</button>
    <div style="display:flex;gap:10px;align-items:center;flex-wrap:wrap">
      <div class="tabs" id="tabs"></div>
      <button class="btn" id="toHome2">← Home</button>
    </div>
  </div></header>
  <div class="main">
    <section class="panel" id="upPanel">
      <h2 class="cz">Upload Photos</h2>
      <form id="upForm">
        <label class="file"><input type="file" id="pin" accept="image/png,image/jpeg,image/webp,image/gif" multiple required><span id="pname">Choose photos…</span></label>
        <select id="cat"><option>Maa</option><option>Pah</option><option selected>SaKa</option></select>
        <button class="go2" id="upBtn" type="submit">+ Upload</button>
      </form>
      <p class="note" id="upNote">JPG, PNG, WebP or GIF · up to 20 MB each</p>
    </section>
    <div class="head"><h3 class="cz" id="ttl">All Photos</h3><p id="cnt">Loading…</p></div>
    <section class="grid" id="grid"></section>
    <div class="empty hidden" id="empty">No photos in this album yet.</div>
  </div>
</div>
</div>

<div id="lock"><div>
  <div class="logo cz" style="font-size:48px;font-weight:900;letter-spacing:.2em">SAKA</div>
  <p class="sub cz">ENTER PASSWORD</p>
  <form id="lkForm"><input id="lkIn" type="password" inputmode="numeric" autocomplete="off" placeholder="••••" aria-label="Password"><button class="go2" type="submit">Unlock</button></form>
  <p class="note" id="lkErr"></p>
</div></div>

<div id="lb" class="hidden">
  <button class="x" id="lbx" aria-label="Close">✕</button>
  <button class="n p" id="lbp" aria-label="Previous">‹</button>
  <button class="n q" id="lbn" aria-label="Next">›</button>
  <img id="lbi" alt="">
  <div id="lbc"></div>
  <button id="lbd" class="hidden">🗑 Delete photo</button>
</div>

<script>
const $ = id => document.getElementById(id);
const CATS = {Maa:['Ennaval','Special moments of Maa'],Pah:['Ennavan','Special moments of Pah'],SaKa:['Together','Precious moments of us']};
let db = null, assets = null, photos = [], filter = 'All', view = [], idx = 0, ready = false, first = true;
const src = id => /^[0-9a-f]{32}$/.test(id || '') ? '/_blob/' + id : '';
const store = {
  get(k){ try { return localStorage.getItem(k); } catch(e){ return null; } },
  set(k,v){ try { localStorage.setItem(k, v); } catch(e){} }
};
let cid = store.get('saka_cid');
if (!cid) { cid = Math.random().toString(36).slice(2); store.set('saka_cid', cid); }
if (store.get('saka_seen') === null) store.set('saka_seen', String(Date.now()));

function toast(msg, ms = 4000){
  const t = document.createElement('div'); t.className = 'toast'; t.textContent = msg;
  $('toasts').appendChild(t); setTimeout(() => t.remove(), ms);
}
function mk(tag, cls, txt){ const e = document.createElement(tag); if (cls) e.className = cls; if (txt) e.textContent = txt; return e; }

function renderHome(){
  const box = $('albums'); box.innerHTML = '';
  Object.keys(CATS).forEach(c => {
    const b = mk('button', 'album');
    const cover = photos.find(p => p.category === c);
    if (cover && src(cover.aid)) { const im = mk('img'); im.src = src(cover.aid); im.alt = c + ' album'; b.appendChild(im); }
    b.appendChild(mk('div', 'shade'));
    const t = mk('div', 'txt');
    t.append(mk('div', 'tag', CATS[c][0]), mk('h3', 'cz', c), mk('small', '', CATS[c][1]), mk('div', 'go', 'EXPLORE ALBUM →'));
    b.appendChild(t); b.onclick = () => openGallery(c); box.appendChild(b);
  });
}
function renderTabs(){
  const t = $('tabs'); t.innerHTML = '';
  ['All', ...Object.keys(CATS)].forEach(c => {
    const b = mk('button', c === filter ? 'on' : '', c); b.onclick = () => { filter = c; renderGallery(); }; t.appendChild(b);
  });
}
function renderGallery(){
  renderTabs();
  view = filter === 'All' ? photos : photos.filter(p => p.category === filter);
  $('ttl').textContent = filter === 'All' ? 'All Photos' : filter + ' Album';
  $('cnt').textContent = ready ? 'Showing ' + view.length + ' photo(s)' : 'Loading…';
  const g = $('grid'); g.innerHTML = '';
  $('empty').classList.toggle('hidden', !ready || view.length > 0);
  view.forEach((p, i) => {
    const b = mk('button', 'ph'); const im = mk('img'); im.src = src(p.aid); im.alt = p.caption || 'Photo'; im.loading = 'lazy';
    const ov = mk('div', 'ov'); ov.append(mk('span', '', p.category), mk('p', '', p.caption || ''));
    b.append(im, ov); b.onclick = () => openLb(i); g.appendChild(b);
  });
}
function openGallery(c){ filter = c; $('home').classList.add('hidden'); $('gallery').classList.remove('hidden'); window.scrollTo(0, 0); renderGallery(); }
function goHome(){ $('gallery').classList.add('hidden'); $('home').classList.remove('hidden'); window.scrollTo(0, 0); }
$('toHome').onclick = $('toHome2').onclick = goHome;

function openLb(i){
  const p = view[i]; if (!p) return; idx = i;
  $('lbi').src = src(p.aid); $('lbc').textContent = p.category + (p.caption ? ' · ' + p.caption : '');
  $('lb').classList.remove('hidden'); resetDel();
}
const stepLb = d => { if (view.length) openLb((idx + d + view.length) % view.length); };
$('lbx').onclick = () => $('lb').classList.add('hidden');
let delArm = false;
function resetDel(){ delArm = false; $('lbd').textContent = '🗑 Delete photo'; }
$('lbd').onclick = async () => {
  const p = view[idx]; if (!p || !db || !assets) return;
  if (!delArm) { delArm = true; $('lbd').textContent = 'Tap again to confirm delete'; return; }
  $('lbd').disabled = true;
  try {
    await db.collection('photos').doc(p.id).delete();
    try { await assets.delete(p.aid); } catch (e) {}
    toast('Photo deleted'); $('lb').classList.add('hidden');
  } catch (e) { toast('Could not delete this photo'); }
  $('lbd').disabled = false; resetDel();
};
$('lbp').onclick = () => stepLb(-1); $('lbn').onclick = () => stepLb(1);
addEventListener('keydown', e => {
  if ($('lb').classList.contains('hidden')) return;
  if (e.key === 'Escape') $('lb').classList.add('hidden');
  if (e.key === 'ArrowLeft') stepLb(-1);
  if (e.key === 'ArrowRight') stepLb(1);
});

function updateBell(){
  const seen = Number(store.get('saka_seen')) || 0;
  const n = photos.filter(p => p.ts > seen && p.by !== cid).length;
  $('bell').classList.toggle('hidden', !ready);
  $('badge').textContent = n; $('badge').classList.toggle('hidden', n === 0);
  $('bell').title = n ? n + ' new photo(s) since your last visit' : 'No new photos';
}
$('bell').onclick = () => {
  store.set('saka_seen', String(Date.now())); updateBell();
  if ($('gallery').classList.contains('hidden')) openGallery('All'); else { filter = 'All'; renderGallery(); }
};

$('pin').onchange = e => {
  const f = e.target.files; $('pname').textContent = !f.length ? 'Choose photos…' : f.length === 1 ? f[0].name : f.length + ' files selected';
};
$('upForm').onsubmit = async e => {
  e.preventDefault();
  const files = [...$('pin').files], category = $('cat').value;
  if (!files.length || !assets || !db) return;
  $('upBtn').disabled = true; let ok = 0;
  for (const f of files) {
    try {
      const r = await assets.upload(f);
      await db.collection('photos').add({aid: r.id, caption: f.name.replace(/\.[^.]+$/, '').slice(0, 120), category, ts: Date.now(), by: cid});
      ok++;
    } catch (err) {
      const c = err && err.code;
      toast((c === 'too_large' ? 'Too large (max 20 MB): ' : c === 'unsupported_type' ? 'Unsupported format: ' : 'Upload failed: ') + f.name);
    }
  }
  $('upBtn').disabled = false;
  if (ok) { toast('✓ Uploaded ' + ok + ' photo(s) to ' + category); $('upForm').reset(); $('pname').textContent = 'Choose photos…'; }
};

(async () => {
  renderHome(); renderGallery();
  try { db = window.claude && await claude.use('db'); } catch (e) {}
  try { assets = window.claude && await claude.use('assets'); } catch (e) {}
  if (!assets) { $('upForm').classList.add('hidden'); $('upNote').textContent = 'Only the site owner and editors can upload photos.'; $('upNote').style.marginTop = '0'; }
  if (assets) $('lbd').classList.remove('hidden');
  if (!db) { $('cnt').textContent = 'Sign in to claude.ai to view the photos.'; return; }
  const t = setTimeout(() => { if (!ready) $('cnt').textContent = 'Taking longer than usual…'; }, 10000);
  db.collection('photos').orderBy('ts', 'desc').onSnapshot(s => {
    clearTimeout(t);
    photos = s.docs.map(d => Object.assign({id: d.id}, d.data()));
    if (!first) s.docChanges().forEach(c => {
      if (c.type !== 'added' || c.doc.metadata.hasPendingWrites) return;
      const d = c.doc.data(); if (d.by !== cid) toast('📸 New photo added to ' + d.category, 6000);
    });
    first = false; ready = true;
    renderHome(); renderGallery(); updateBell();
  }, () => { clearTimeout(t); $('cnt').textContent = 'Could not load photos.'; });
})();

/* password lock */
const PW_HASH = 'b35b93bc107d0201fa17e62684a73ddd68f0973650fb654a7000f263963bbfbc';
async function pwHash(s){
  try {
    const b = await crypto.subtle.digest('SHA-256', new TextEncoder().encode('saka:' + s));
    return [...new Uint8Array(b)].map(x => x.toString(16).padStart(2, '0')).join('');
  } catch (e) { return s === String.fromCharCode(48, 50, 49, 54) ? PW_HASH : ''; }
}
if (store.get('saka_ok') === PW_HASH) $('lock').classList.add('hidden');
$('lkForm').onsubmit = async e => {
  e.preventDefault();
  if (await pwHash($('lkIn').value.trim()) === PW_HASH) {
    store.set('saka_ok', PW_HASH); $('lock').classList.add('hidden'); $('lkIn').value = ''; $('lkErr').textContent = '';
  } else { $('lkErr').textContent = 'Wrong password. Try again.'; $('lkIn').value = ''; }
};

/* floating hearts & sparkles */
const cv = $('fx'), cx = cv.getContext('2d'); let ps = [];
const fit = () => { cv.width = innerWidth; cv.height = innerHeight; }; addEventListener('resize', fit); fit();
const mkP = init => ({x: Math.random() * cv.width, y: init ? Math.random() * cv.height : -30, r: Math.random() * 5 + 3, v: Math.random() * .8 + .4, h: Math.random() > .5, a: Math.random() * .5 + .2});
for (let i = 0; i < 40; i++) ps.push(mkP(true));
(function loop(){
  cx.clearRect(0, 0, cv.width, cv.height);
  ps.forEach((p, i) => {
    p.y += p.v; if (p.y > cv.height + 30) ps[i] = mkP(false);
    cx.globalAlpha = p.a; cx.fillStyle = p.h ? '#ff4d6d' : '#d4af37';
    cx.beginPath(); cx.arc(p.x, p.y, p.r, 0, 6.283); cx.fill();
  });
  requestAnimationFrame(loop);
})();
</script>
</body>
</html>
