<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Sumit Karkhile · Backend & Full-Stack Engineer</title>
<style>
:root{--bg:#f6f8fa;--card:#fff;--ink:#0d1117;--mute:#57606a;--line:#d0d7de;--acc:#007c85;--acc2:#0d47a1;--glow:rgba(0,173,181,.15);box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0d1117;--card:#161b22;--ink:#e6edf3;--mute:#8b949e;--line:#30363d;--acc:#00adb5;--acc2:#4c8dff;--glow:rgba(0,173,181,.18)}}
:root[data-theme="dark"]{--bg:#0d1117;--card:#161b22;--ink:#e6edf3;--mute:#8b949e;--line:#30363d;--acc:#00adb5;--acc2:#4c8dff;--glow:rgba(0,173,181,.18)}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;overflow-x:hidden}
canvas#bg{position:fixed;inset:0;width:100%;height:100%;z-index:0;opacity:.55;pointer-events:none}
main,nav{position:relative;z-index:1}
.wrap{max-width:1000px;margin:0 auto;padding:0 20px}
nav{position:sticky;top:env(safe-area-inset-top,0px);backdrop-filter:blur(10px);background:color-mix(in srgb,var(--bg) 80%,transparent);border-bottom:1px solid var(--line);z-index:5}
nav .wrap{display:flex;gap:14px;align-items:center;height:52px;overflow-x:auto;white-space:nowrap}
nav a{color:var(--mute);text-decoration:none;font-size:14px}nav a:hover{color:var(--acc)}
nav b{color:var(--acc);margin-right:auto;font-family:ui-monospace,Menlo,monospace}
button{font:inherit;cursor:pointer}
.ico{background:none;border:1px solid var(--line);color:var(--ink);border-radius:8px;padding:4px 10px}
.hero{padding:72px 0 40px}
.tag{display:inline-block;font:12px ui-monospace,Menlo,monospace;color:var(--acc);border:1px solid var(--acc);border-radius:99px;padding:3px 12px;margin-bottom:16px}
h1{font-size:clamp(2.4rem,7vw,4.4rem);line-height:1.05;margin:0 0 12px;letter-spacing:-.03em}
h1 span{background:linear-gradient(90deg,var(--acc),var(--acc2));-webkit-background-clip:text;background-clip:text;color:transparent}
.type{font:clamp(15px,3vw,20px) ui-monospace,Menlo,monospace;color:var(--acc);min-height:1.8em}
.type::after{content:"▍";animation:b 1s steps(1) infinite}@keyframes b{50%{opacity:0}}
.cta{display:flex;flex-wrap:wrap;gap:10px;margin-top:24px}
.btn{display:inline-block;padding:10px 18px;border-radius:10px;text-decoration:none;font-weight:600;font-size:14px;border:1px solid var(--line);color:var(--ink);background:var(--card);transition:.2s}
.btn:hover{transform:translateY(-2px);border-color:var(--acc)}
.btn.p{background:linear-gradient(90deg,var(--acc2),var(--acc));color:#fff;border:0}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:14px;margin:36px 0}
.stat{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px;transition:.25s}
.stat:hover{box-shadow:0 0 0 4px var(--glow);transform:translateY(-3px)}
.stat .n{font-size:2.1rem;font-weight:800;color:var(--acc);font-variant-numeric:tabular-nums}
.stat .l{color:var(--mute);font-size:13px}
section{padding:36px 0}
h2{font-size:1.5rem;margin:0 0 6px}h2::before{content:"// ";color:var(--acc);font-family:ui-monospace,Menlo,monospace}
.sub{color:var(--mute);margin:0 0 20px}
.hr{background:var(--card);border:1px solid var(--acc);border-radius:14px;padding:18px 20px;box-shadow:0 0 0 4px var(--glow)}
.hr label{display:flex;gap:10px;align-items:center;font-weight:600;cursor:pointer}
.hr ul{margin:12px 0 0;padding-left:20px;display:none}.hr.on ul{display:block}
.tabs{display:flex;flex-wrap:wrap;gap:8px;margin-bottom:16px}
.chip{border:1px solid var(--line);background:var(--card);color:var(--ink);border-radius:99px;padding:5px 14px;font-size:13px}
.chip.on,.chip:hover{border-color:var(--acc);color:var(--acc)}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:16px}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:18px;transition:.25s}
.card:hover{border-color:var(--acc);transform:translateY(-3px)}
.card h3{margin:0 0 4px}.card small{color:var(--mute)}
.card .more{display:none;margin-top:10px;color:var(--mute);font-size:14px}.card.open .more{display:block}
.card .row{display:flex;flex-wrap:wrap;gap:6px;margin-top:10px}
.card code,.sk{font:12px ui-monospace,Menlo,monospace;background:var(--glow);color:var(--acc);padding:2px 8px;border-radius:6px}
.skills{display:flex;flex-wrap:wrap;gap:8px}
.sk{font-size:13px;padding:5px 12px;transition:.2s}.sk.dim{opacity:.15}
.term{background:#0d1117;color:#c9d1d9;border:1px solid #30363d;border-radius:12px;font:14px/1.5 ui-monospace,Menlo,monospace;overflow:hidden}
.term .bar{background:#161b22;padding:8px 14px;color:#8b949e;font-size:12px}
.term .out{padding:14px;height:230px;overflow-y:auto;white-space:pre-wrap}
.term .out i{color:#00adb5;font-style:normal}
.term form{display:flex;border-top:1px solid #30363d}
.term input{flex:1;background:none;border:0;color:#e6edf3;font:inherit;padding:12px 14px;outline:0;min-width:0}
.term span.p{color:#00adb5;padding:12px 0 12px 14px}
.reveal{opacity:0;transform:translateY(20px);transition:.6s}.reveal.in{opacity:1;transform:none}
footer{text-align:center;color:var(--mute);padding:40px 0 60px;font-size:14px}
</style>
</head>
<body>
<canvas id="bg"></canvas>
<nav><div class="wrap"><b>sumit@pict:~$</b><a href="#stats">Stats</a><a href="#projects">Projects</a><a href="#skills">Skills</a><a href="#terminal">Terminal</a><a href="#contact">Contact</a><button class="ico" id="theme" aria-label="Toggle theme">◐</button></div></nav>
<main class="wrap">
<div class="hero">
  <span class="tag">● Open for SDE Intern / Full-Time roles · Pune, India</span>
  <h1>Hi, I’m <span>Sumit Karkhile</span></h1>
  <div class="type" id="type"></div>
  <p class="sub" style="max-width:640px;margin-top:14px">Final-year Computer Engineering student at PICT Pune who builds production-grade Java backends, ships full-stack products, and wires in generative AI where it actually helps.</p>
  <div class="cta">
    <a class="btn p" href="https://racing-teal-dqrrc87.tmp.now/" target="_blank" rel="noopener">⚡ Launch 3D Portfolio</a>
    <a class="btn" href="https://www.linkedin.com/in/sumit-karkhile-73019a290" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn" href="mailto:karkhilesumit5654@gmail.com">Hire me</a>
  </div>
</div>

<div class="hr" id="hr">
  <label><input type="checkbox" id="hrt"> 👔 Recruiter mode: show me the 30-second summary</label>
  <ul>
    <li><b>Who:</b> Final-year CE at PICT Pune, <b>9.45 CGPA</b>.</li>
    <li><b>Core stack:</b> Java 21, Spring Boot 3, Spring Security (JWT/RBAC), React 19, TypeScript, MySQL/PostgreSQL, Docker, AWS S3.</li>
    <li><b>Proof of problem-solving:</b> LeetCode Knight (<b>1950</b>), 700+ DSA problems, CodeChef 3★ (1650).</li>
    <li><b>Shipped:</b> LectureLens (real-time WebRTC + Gemini Vision), PageForge (AI document suite), Canteen Management (RBAC + QR vouchers).</li>
    <li><b>Looking for:</b> SDE Intern or full-time backend / full-stack roles.</li>
  </ul>
</div>

<section id="stats" class="reveal">
  <h2>Numbers</h2><p class="sub">Hover the cards. Counters animate on scroll.</p>
  <div class="stats">
    <div class="stat"><div class="n" data-v="9.45" data-d="2">0</div><div class="l">CGPA / 10 · PICT Pune</div></div>
    <div class="stat"><div class="n" data-v="1950">0</div><div class="l">LeetCode max rating · Knight</div></div>
    <div class="stat"><div class="n" data-v="700" data-s="+">0</div><div class="l">DSA problems solved</div></div>
    <div class="stat"><div class="n" data-v="1650">0</div><div class="l">CodeChef rating · 3★</div></div>
  </div>
</section>

<section id="projects" class="reveal">
  <h2>Projects</h2><p class="sub">Filter by focus, click a card for details.</p>
  <div class="tabs" id="ptabs"><button class="chip on" data-f="all">All</button><button class="chip" data-f="backend">Backend</button><button class="chip" data-f="ai">AI</button><button class="chip" data-f="fullstack">Full-stack</button></div>
  <div class="grid" id="pgrid"></div>
</section>

<section id="skills" class="reveal">
  <h2>Skills</h2><p class="sub">Pick a category to highlight.</p>
  <div class="tabs" id="stabs"></div>
  <div class="skills" id="sgrid"></div>
</section>

<section id="terminal" class="reveal">
  <h2>Terminal</h2><p class="sub">Try <b>help</b>. Commands: about, skills, projects, stats, contact, portfolio, clear.</p>
  <div class="term"><div class="bar">● ● ●  sumit@pict-workstation</div><div class="out" id="out"></div>
  <form id="tf"><span class="p">$</span><input id="ti" autocomplete="off" autocapitalize="off" spellcheck="false" aria-label="Terminal command" placeholder="type a command…"></form></div>
</section>

<section id="contact" class="reveal">
  <h2>Let’s talk</h2>
  <div class="cta">
    <a class="btn p" href="mailto:karkhilesumit5654@gmail.com">karkhilesumit5654@gmail.com</a>
    <a class="btn" href="https://www.linkedin.com/in/sumit-karkhile-73019a290" target="_blank" rel="noopener">LinkedIn</a>
    <a class="btn" href="https://leetcode.com/u/sumit_307/" target="_blank" rel="noopener">LeetCode</a>
    <a class="btn" href="https://www.codechef.com/users/sai_812" target="_blank" rel="noopener">CodeChef</a>
    <a class="btn" href="https://github.com/Sai600858" target="_blank" rel="noopener">GitHub</a>
  </div>
</section>
</main>
<footer>“Discipline and clean architecture turn complex algorithms into impactful software.”</footer>

<script>
const P=[
{t:"LectureLens",c:["backend","ai","fullstack"],s:["Java 21","Spring Boot 3","React 18","mediasoup SFU","Gemini Vision"],d:"Capstone platform.",m:"Real-time WebRTC classroom streaming, live whiteboard OCR with Gemini visual analysis, and RAG-powered student Q&A.",l:"https://github.com/Sai600858"},
{t:"PageForge",c:["backend","ai","fullstack"],s:["Spring Boot 3.3","React 19","MySQL","Gemini AI","Docker","AWS S3"],d:"AI document engineering suite.",m:"Text summarization, OCR extraction, watermarking and secure PDF transformation, containerized and backed by S3.",l:"https://github.com/Sai600858/Page-Forge"},
{t:"Canteen Management",c:["backend","fullstack"],s:["Spring Security","MySQL","JWT","QR Codes"],d:"Cafeteria platform.",m:"Role-based access control, HTTP-only cookie auth, QR voucher redemption and handling of high concurrency.",l:"https://github.com/Sai600858/CanteenSystem"},
{t:"AI Resume Intelligence",c:["ai"],s:["Python","Sentence-BERT","Transformers","React.js"],d:"PICT research project.",m:"Automated PDF entity extraction plus dense semantic cosine matching between resumes and job descriptions.",l:"https://racing-teal-dqrrc87.tmp.now/"}];
const S={Languages:["Java 21","TypeScript","JavaScript","C++","Python","SQL"],Backend:["Spring Boot 3.3","Spring Security","JPA / Hibernate","REST","WebSocket","Microservices"],Frontend:["React 19","Next.js","Vite","Tailwind CSS"],"Data & Cloud":["PostgreSQL","MySQL","Redis","Flyway","Docker","AWS S3","Nginx","Vercel"],"AI & Tools":["Gemini API (RAG)","Sentence-BERT","GitHub Actions","Git","Linux","Maven","Postman"]};
const $=s=>document.querySelector(s),el=(t,c,x)=>{const e=document.createElement(t);if(c)e.className=c;if(x)e.textContent=x;return e};

// theme
$("#theme").onclick=()=>{const r=document.documentElement,d=r.dataset.theme?r.dataset.theme==="dark":matchMedia("(prefers-color-scheme:dark)").matches;r.dataset.theme=d?"light":"dark"};
// typing
const L=["Java Backend Architect • Spring Boot Microservices","LeetCode Knight 🥇 1950 rating • 700+ problems","Full-Stack: React 19 • TypeScript • Vite","AI & RAG: Gemini Vision • Sentence-BERT","PICT Pune • 9.45 CGPA"];
let li=0,ci=0,del=false;(function tick(){const w=L[li];ci+=del?-1:1;$("#type").textContent=w.slice(0,ci);let t=del?25:55;if(!del&&ci===w.length){del=true;t=1500}else if(del&&ci===0){del=false;li=(li+1)%L.length;t=300}setTimeout(tick,t)})();
// recruiter
$("#hrt").onchange=e=>$("#hr").classList.toggle("on",e.target.checked);
// projects
function drawP(f){const g=$("#pgrid");g.replaceChildren();P.filter(p=>f==="all"||p.c.includes(f)).forEach(p=>{const c=el("div","card");c.append(el("h3","",p.t),el("small","",p.d));const m=el("div","more",p.m+" ");const a=el("a","","View code ↗");a.href=p.l;a.target="_blank";a.rel="noopener";a.style.color="var(--acc)";m.append(a);const r=el("div","row");p.s.forEach(x=>r.append(el("code","",x)));c.append(r,m);c.onclick=e=>{if(e.target.tagName!=="A")c.classList.toggle("open")};g.append(c)})}
$("#ptabs").onclick=e=>{const b=e.target.closest("button");if(!b)return;document.querySelectorAll("#ptabs .chip").forEach(x=>x.classList.toggle("on",x===b));drawP(b.dataset.f)};drawP("all");
// skills
const st=$("#stabs");["All",...Object.keys(S)].forEach((k,i)=>{const b=el("button","chip"+(i?"":" on"),k);b.dataset.k=k;st.append(b)});
function drawS(k){const g=$("#sgrid");g.replaceChildren();Object.entries(S).forEach(([c,a])=>a.forEach(x=>{const s=el("span","sk"+(k!=="All"&&k!==c?" dim":""),x);g.append(s)}))}
st.onclick=e=>{const b=e.target.closest("button");if(!b)return;st.querySelectorAll(".chip").forEach(x=>x.classList.toggle("on",x===b));drawS(b.dataset.k)};drawS("All");
// counters + reveal
const io=new IntersectionObserver(es=>es.forEach(e=>{if(!e.isIntersecting)return;e.target.classList.add("in");e.target.querySelectorAll(".n").forEach(n=>{if(n.dataset.done)return;n.dataset.done=1;const v=+n.dataset.v,d=+(n.dataset.d||0),s=n.dataset.s||"",t0=performance.now();(function f(t){const p=Math.min((t-t0)/1400,1),k=1-Math.pow(1-p,3);n.textContent=(v*k).toFixed(d)+(p===1?s:"");if(p<1)requestAnimationFrame(f)})(t0)})}),{threshold:.2});
document.querySelectorAll(".reveal").forEach(x=>io.observe(x));
// terminal
const out=$("#out");const say=(t,i)=>{const d=el("div");if(i){const s=el("i","",t);d.append(s)}else d.textContent=t;out.append(d);out.scrollTop=out.scrollHeight};
const C={help:()=>"Commands: about, skills, projects, stats, contact, portfolio, clear",
about:()=>"Sumit Karkhile · Final-year CE @ PICT Pune (9.45 CGPA)\nBackend / full-stack engineer with applied AI. Target: SDE Intern | Full-Time SDE.",
skills:()=>Object.entries(S).map(([k,v])=>k+": "+v.join(", ")).join("\n"),
projects:()=>P.map(p=>"▸ "+p.t+" — "+p.d).join("\n"),
stats:()=>"CGPA 9.45 | LeetCode Knight 1950 | 700+ DSA | CodeChef 3★ 1650",
contact:()=>"karkhilesumit5654@gmail.com\nlinkedin.com/in/sumit-karkhile-73019a290",
portfolio:()=>{window.open("https://racing-teal-dqrrc87.tmp.now/","_blank","noopener");return"Launching 3D portfolio… (allow pop-ups if nothing opens)"},
clear:()=>{out.replaceChildren();return null},
sudo:()=>"Nice try. But hire me and I’ll gladly take on-call."};
say("Welcome. Type 'help' to begin.",1);
$("#tf").onsubmit=e=>{e.preventDefault();const i=$("#ti"),v=i.value.trim().toLowerCase();i.value="";if(!v)return;say("$ "+v,1);const f=C[v.split(" ")[0]];const r=f?f():"command not found: "+v.slice(0,40);if(r)say(r)};
// particle background
(function(){const c=$("#bg"),x=c.getContext("2d");let w,h,p=[];const rs=()=>{w=c.width=innerWidth;h=c.height=innerHeight;p=Array.from({length:Math.min(70,w/16|0)},()=>({x:Math.random()*w,y:Math.random()*h,vx:(Math.random()-.5)*.4,vy:(Math.random()-.5)*.4}))};rs();addEventListener("resize",rs);let mx=-999,my=-999;addEventListener("pointermove",e=>{mx=e.clientX;my=e.clientY});
(function f(){x.clearRect(0,0,w,h);const col=getComputedStyle(document.documentElement).getPropertyValue("--acc").trim()||"#00adb5";x.fillStyle=col;x.strokeStyle=col;p.forEach((a,i)=>{a.x=(a.x+a.vx+w)%w;a.y=(a.y+a.vy+h)%h;x.beginPath();x.arc(a.x,a.y,1.6,0,6.3);x.fill();for(let j=i+1;j<p.length;j++){const b=p[j],d=Math.hypot(a.x-b.x,a.y-b.y);if(d<110){x.globalAlpha=.25*(1-d/110);x.beginPath();x.moveTo(a.x,a.y);x.lineTo(b.x,b.y);x.stroke()}}const dm=Math.hypot(a.x-mx,a.y-my);if(dm<150){x.globalAlpha=.5;x.beginPath();x.moveTo(a.x,a.y);x.lineTo(mx,my);x.stroke()}x.globalAlpha=1});requestAnimationFrame(f)})()})();
</script>
</body>
</html>
