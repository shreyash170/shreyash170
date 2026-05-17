
<style>
*{box-sizing:border-box;margin:0;padding:0}
.wrap{font-family:var(--font-sans);padding:1.5rem}
.hero{text-align:center;padding:2rem 1rem 2.5rem;border-bottom:0.5px solid var(--color-border-tertiary);margin-bottom:2rem}
.avatar{width:72px;height:72px;border-radius:50%;background:var(--color-background-secondary);border:0.5px solid var(--color-border-secondary);display:flex;align-items:center;justify-content:center;font-size:24px;font-weight:500;color:var(--color-text-primary);margin:0 auto 1rem}
.hero-name{font-size:28px;font-weight:500;color:var(--color-text-primary);letter-spacing:-0.5px}
.hero-role{font-size:14px;color:var(--color-text-secondary);margin-top:4px}
.divider-dot{margin:0 6px;opacity:0.4}
.pill-row{display:flex;flex-wrap:wrap;justify-content:center;gap:6px;margin-top:1rem}
.pill{font-size:11px;font-weight:500;padding:3px 10px;border-radius:999px;border:0.5px solid var(--color-border-secondary);color:var(--color-text-secondary);background:var(--color-background-secondary)}
.sec{margin-bottom:2rem}
.sec-hd{font-size:11px;font-weight:500;letter-spacing:.1em;text-transform:uppercase;color:var(--color-text-secondary);margin-bottom:1rem;display:flex;align-items:center;gap:8px}
.sec-hd::after{content:'';flex:1;height:0.5px;background:var(--color-border-tertiary)}
.exp-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:10px}
.exp-card{background:var(--color-background-primary);border:0.5px solid var(--color-border-tertiary);border-radius:var(--border-radius-lg);padding:1rem;position:relative;overflow:hidden}
.exp-card-accent{position:absolute;top:0;left:0;right:0;height:3px;border-radius:var(--border-radius-lg) var(--border-radius-lg) 0 0}
.exp-icon{font-size:22px;margin-bottom:10px}
.exp-title{font-size:13px;font-weight:500;color:var(--color-text-primary)}
.exp-sub{font-size:11px;color:var(--color-text-secondary);margin-top:3px;line-height:1.5}
.exp-badge{display:inline-block;font-size:10px;font-weight:500;padding:2px 8px;border-radius:999px;margin-top:10px}
.b-blue{background:#E6F1FB;color:#0C447C}
.b-green{background:#EAF3DE;color:#27500A}
.b-purple{background:#EEEDFE;color:#3C3489}
.b-amber{background:#FAEEDA;color:#633806}
.acc-blue{background:#378ADD}
.acc-green{background:#639922}
.acc-purple{background:#7F77DD}
.acc-amber{background:#BA7517}
@media(prefers-color-scheme:dark){
.b-blue{background:#0C447C;color:#B5D4F4}
.b-green{background:#27500A;color:#C0DD97}
.b-purple{background:#3C3489;color:#CECBF6}
.b-amber{background:#633806;color:#FAC775}
}
.stack-row{display:flex;align-items:flex-start;gap:10px;margin-bottom:10px}
.stack-lbl{font-size:11px;font-weight:500;color:var(--color-text-secondary);min-width:72px;padding-top:4px}
.pills{display:flex;flex-wrap:wrap;gap:5px}
.tech-pill{font-size:11px;font-weight:500;padding:3px 9px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);color:var(--color-text-primary);background:var(--color-background-secondary)}
.stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:2rem}
.stat-card{background:var(--color-background-secondary);border-radius:var(--border-radius-md);padding:.875rem 1rem}
.stat-val{font-size:22px;font-weight:500;color:var(--color-text-primary)}
.stat-lbl{font-size:11px;color:var(--color-text-secondary);margin-top:2px}
.connect-row{display:flex;gap:8px;flex-wrap:wrap}
.connect-btn{display:inline-flex;align-items:center;gap:6px;font-size:13px;font-weight:500;padding:7px 14px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);color:var(--color-text-primary);background:var(--color-background-primary);cursor:pointer;text-decoration:none}
.connect-btn:hover{background:var(--color-background-secondary)}
.copy-wrap{text-align:right;margin-bottom:.5rem}
.copy-btn{font-size:11px;font-family:var(--font-sans);padding:4px 12px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-secondary);background:var(--color-background-primary);cursor:pointer;color:var(--color-text-secondary)}
.copy-btn:hover{color:var(--color-text-primary)}
.md-block{background:var(--color-background-secondary);border-radius:var(--border-radius-lg);padding:1.25rem 1.5rem;font-family:var(--font-mono);font-size:11.5px;line-height:1.8;color:var(--color-text-primary);white-space:pre-wrap;overflow-x:auto;max-height:400px;overflow-y:auto}
.tabs{display:flex;gap:4px;margin-bottom:1.25rem}
.tab{font-size:13px;padding:5px 12px;border-radius:var(--border-radius-md);border:0.5px solid var(--color-border-tertiary);cursor:pointer;color:var(--color-text-secondary);background:transparent}
.tab.on{background:var(--color-background-secondary);color:var(--color-text-primary);border-color:var(--color-border-secondary);font-weight:500}
.pane{display:none}.pane.on{display:block}
</style>

<div class="wrap">

<div class="hero">
  <div class="avatar">SG</div>
  <div class="hero-name">Shreyash Gupta</div>
  <div class="hero-role">iOS Developer <span class="divider-dot">·</span> Full Stack <span class="divider-dot">·</span> DSA</div>
  <div class="pill-row">
    <span class="pill"><i class="ti ti-map-pin" aria-hidden="true"></i> India</span>
    <span class="pill">Open to opportunities</span>
    <span class="pill">2.4+ yrs experience</span>
  </div>
</div>

<div class="tabs">
  <button class="tab on" onclick="sw('preview',this)">Preview</button>
  <button class="tab" onclick="sw('markdown',this)">Markdown source</button>
</div>

<div id="pane-preview" class="pane on">

  <div class="stats-row">
    <div class="stat-card">
      <div class="stat-val">2.4+</div>
      <div class="stat-lbl">Years iOS dev</div>
    </div>
    <div class="stat-card">
      <div class="stat-val">5+</div>
      <div class="stat-lbl">Technologies</div>
    </div>
    <div class="stat-card">
      <div class="stat-val">Full</div>
      <div class="stat-lbl">Stack capable</div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-hd">About</div>
    <p style="font-size:14px;color:var(--color-text-primary);line-height:1.8">
      Software engineer with <strong>2.4+ years</strong> of production iOS experience building Swift apps from scratch.
      Equally comfortable on the backend with Node.js and the frontend with React.
      Strong problem solver with deep hands-on practice in data structures and algorithms using Java.
      I care about clean code, thoughtful architecture, and great user experience.
    </p>
  </div>

  <div class="sec">
    <div class="sec-hd">Experience</div>
    <div class="exp-grid">
      <div class="exp-card">
        <div class="exp-card-accent acc-blue"></div>
        <div class="exp-icon"><i class="ti ti-brand-apple" aria-hidden="true" style="color:#378ADD"></i></div>
        <div class="exp-title">iOS Development</div>
        <div class="exp-sub">Swift · SwiftUI · UIKit · Xcode · CocoaPods</div>
        <span class="exp-badge b-blue">2.4+ years</span>
      </div>
      <div class="exp-card">
        <div class="exp-card-accent acc-green"></div>
        <div class="exp-icon"><i class="ti ti-server" aria-hidden="true" style="color:#639922"></i></div>
        <div class="exp-title">Backend</div>
        <div class="exp-sub">Node.js · Express · REST APIs · Java</div>
        <span class="exp-badge b-green">Hands-on</span>
      </div>
      <div class="exp-card">
        <div class="exp-card-accent acc-purple"></div>
        <div class="exp-icon"><i class="ti ti-layout-2" aria-hidden="true" style="color:#7F77DD"></i></div>
        <div class="exp-title">Frontend</div>
        <div class="exp-sub">React · JavaScript · TypeScript · HTML · CSS</div>
        <span class="exp-badge b-purple">Hands-on</span>
      </div>
      <div class="exp-card">
        <div class="exp-card-accent acc-amber"></div>
        <div class="exp-icon"><i class="ti ti-binary-tree" aria-hidden="true" style="color:#BA7517"></i></div>
        <div class="exp-title">DSA</div>
        <div class="exp-sub">Java · Arrays · Trees · Graphs · DP</div>
        <span class="exp-badge b-amber">Strong</span>
      </div>
    </div>
  </div>

  <div class="sec">
    <div class="sec-hd">Tech stack</div>
    <div class="stack-row"><span class="stack-lbl">Mobile</span><div class="pills"><span class="tech-pill">Swift</span><span class="tech-pill">SwiftUI</span><span class="tech-pill">UIKit</span><span class="tech-pill">Xcode</span></div></div>
    <div class="stack-row"><span class="stack-lbl">Backend</span><div class="pills"><span class="tech-pill">Node.js</span><span class="tech-pill">Express</span><span class="tech-pill">Java</span></div></div>
    <div class="stack-row"><span class="stack-lbl">Frontend</span><div class="pills"><span class="tech-pill">React</span><span class="tech-pill">JavaScript</span><span class="tech-pill">TypeScript</span><span class="tech-pill">HTML</span><span class="tech-pill">CSS</span></div></div>
    <div class="stack-row"><span class="stack-lbl">Databases</span><div class="pills"><span class="tech-pill">MySQL</span><span class="tech-pill">MongoDB</span><span class="tech-pill">Firebase</span><span class="tech-pill">PostgreSQL</span></div></div>
    <div class="stack-row"><span class="stack-lbl">Tools</span><div class="pills"><span class="tech-pill">Git</span><span class="tech-pill">GitHub</span><span class="tech-pill">Docker</span><span class="tech-pill">AWS</span><span class="tech-pill">Linux</span><span class="tech-pill">Figma</span></div></div>
  </div>

  <div class="sec">
    <div class="sec-hd">Connect</div>
    <div class="connect-row">
      <a class="connect-btn" href="https://linkedin.com" target="_blank"><i class="ti ti-brand-linkedin" aria-hidden="true"></i> LinkedIn</a>
      <a class="connect-btn" href="mailto:"><i class="ti ti-mail" aria-hidden="true"></i> Email</a>
      <a class="connect-btn" href="https://github.com" target="_blank"><i class="ti ti-brand-github" aria-hidden="true"></i> GitHub</a>
    </div>
  </div>

</div>

<div id="pane-markdown" class="pane">
  <div class="copy-wrap"><button class="copy-btn" onclick="copyMd()">Copy all</button></div>
  <div class="md-block" id="mdsrc"></div>
</div>

</div>

<script>
const md = `<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=210&color=gradient&customColorList=2,12,20&text=Shreyash%20Gupta&fontSize=42&fontAlignY=38&desc=iOS%20Developer%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20DSA&descSize=16&descAlignY=58&animation=fadeIn"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=SF+Mono&size=18&duration=2800&pause=1000&color=EAEAEA&center=true&vCenter=true&width=700&lines=2.4%2B+years+of+iOS+development;Swift+%7C+SwiftUI+%7C+UIKit;Node.js+%7C+React+%7C+Full+Stack;Strong+DSA+foundation+in+Java"/>

<br/>

![](https://img.shields.io/badge/iOS-2.4%2B%20Years-0A84FF?style=flat-square&logo=apple&logoColor=white)
![](https://img.shields.io/badge/Backend-Node.js-3C873A?style=flat-square&logo=nodedotjs&logoColor=white)
![](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![](https://img.shields.io/badge/DSA-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![](https://img.shields.io/badge/Open%20to-Opportunities-6E40C9?style=flat-square)

</div>

---

## About Me

Software engineer with **2.4+ years** of production iOS experience building Swift apps from scratch.
Equally comfortable on the backend with Node.js and the frontend with React.
Strong problem solver with deep hands-on practice in data structures and algorithms using Java.
I care about clean code, thoughtful architecture, and great user experience.

---

## Experience

<div align="center">
<table border="0" cellspacing="0" cellpadding="0">
<tr>
<td width="200" align="center">

### 📱 iOS Development
\`\`\`
Swift · SwiftUI · UIKit
Xcode · CocoaPods
\`\`\`
![](https://img.shields.io/badge/2.4%2B%20years-0A84FF?style=flat-square)

</td>
<td width="200" align="center">

### 🖥 Backend
\`\`\`
Node.js · Express
REST APIs · Java
\`\`\`
![](https://img.shields.io/badge/Hands--on-3C873A?style=flat-square)

</td>
<td width="200" align="center">

### 🌐 Frontend
\`\`\`
React · JavaScript
TypeScript · HTML · CSS
\`\`\`
![](https://img.shields.io/badge/Hands--on-7B68EE?style=flat-square)

</td>
<td width="200" align="center">

### 🧠 DSA
\`\`\`
Java · Arrays · Trees
Graphs · DP · Sorting
\`\`\`
![](https://img.shields.io/badge/Strong-ED8B00?style=flat-square)

</td>
</tr>
</table>
</div>

---

## Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=swift,java,nodejs,react,typescript,javascript,mysql,mongodb,firebase,postgres,docker,aws,git,linux,figma&theme=dark&perline=8"/>
</div>

---

## GitHub Stats

<div align="center">
<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true&count_private=true"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=github_dark&hide_border=true"/>
</div>

---

## Connect

<div align="center">
<a href="https://linkedin.com/in/YOUR_LINKEDIN">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:YOUR_EMAIL">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://github.com/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</div>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=2,12,20&section=footer"/>`;

document.getElementById('mdsrc').textContent = md;

function sw(name, el) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('on'));
  document.querySelectorAll('.pane').forEach(p => p.classList.remove('on'));
  el.classList.add('on');
  document.getElementById('pane-' + name).classList.add('on');
}

function copyMd() {
  navigator.clipboard.writeText(md).then(() => {
    const b = document.querySelector('.copy-btn');
    b.textContent = 'Copied!';
    setTimeout(() => b.textContent = 'Copy all', 2000);
  });
}
</script>
