<div align="center">
  <svg viewBox="0 0 1200 280" width="100%" height="auto" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#0b1220"/>
        <stop offset="70%" stop-color="#0a0a0f"/>
        <stop offset="100%" stop-color="#111827"/>
      </linearGradient>
      <linearGradient id="txt" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#a78bfa"/>
        <stop offset="50%" stop-color="#60a5fa"/>
        <stop offset="100%" stop-color="#34d399"/>
      </linearGradient>
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="b"/>
        <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
      <symbol id="petal" viewBox="0 0 40 40">
        <path d="M20 4 C26 10, 30 18, 20 36 C10 18, 14 10, 20 4 Z" fill="#f472b6"/>
        <path d="M20 4 C26 10, 30 18, 20 36" fill="none" stroke="#f9a8d4" stroke-width="1.2" opacity="0.7"/>
      </symbol>
      <style>
        @keyframes twinkle { 0%,100%{opacity:.15} 50%{opacity:.6} }
        @keyframes drift {
          0%{ transform:translateY(-40px) translateX(0) rotate(0); opacity:0 }
          5%{ opacity:1 }
          100%{ transform:translateY(360px) translateX(-80px) rotate(360deg); opacity:0 }
        }
      </style>
    </defs>

    <rect width="1200" height="280" fill="url(#bg)"/>
    <g>
      <circle cx="80" cy="60" r="2.2" fill="#93c5fd" style="animation:twinkle 2.6s infinite .2s"/>
      <circle cx="240" cy="30" r="1.6" fill="#c4b5fd" style="animation:twinkle 3.1s infinite .6s"/>
      <circle cx="360" cy="100" r="1.8" fill="#a7f3d0" style="animation:twinkle 2.4s infinite .1s"/>
      <circle cx="520" cy="50" r="2.0" fill="#93c5fd" style="animation:twinkle 2.8s infinite .9s"/>
      <circle cx="700" cy="40" r="1.5" fill="#c4b5fd" style="animation:twinkle 2.9s infinite .3s"/>
      <circle cx="880" cy="90" r="2.2" fill="#a7f3d0" style="animation:twinkle 2.2s infinite .5s"/>
      <circle cx="1040" cy="30" r="1.7" fill="#93c5fd" style="animation:twinkle 3.2s infinite .7s"/>
    </g>

    <ellipse cx="600" cy="170" rx="340" ry="60" fill="#60a5fa" opacity=".09" filter="url(#glow)"/>

    <g transform="translate(0,10)">
      <text x="50%" y="130" text-anchor="middle"
            fill="url(#txt)" filter="url(#glow)"
            font-family="ui-sans-serif, Inter, system-ui"
            font-weight="800" font-size="54">Kaw — Supavich</text>

      <text x="50%" y="170" text-anchor="middle" fill="#9ca3af"
            font-family="ui-sans-serif, Inter, system-ui"
            font-weight="600" font-size="22" letter-spacing="3">
        オタク・フロントエンド・デベロッパー
      </text>
    </g>

    <g opacity="0.85">
      <use href="#petal" x="1100" y="-20" width="28" height="28" style="animation:drift 9s linear infinite .2s"/>
      <use href="#petal" x="980"  y="-30" width="24" height="24" style="animation:drift 10s linear infinite 1.1s"/>
      <use href="#petal" x="860"  y="-25" width="32" height="32" style="animation:drift 11s linear infinite .8s"/>
      <use href="#petal" x="740"  y="-35" width="26" height="26" style="animation:drift 9.5s linear infinite .4s"/>
      <use href="#petal" x="620"  y="-40" width="30" height="30" style="animation:drift 10.5s linear infinite 1.6s"/>
      <use href="#petal" x="500"  y="-28" width="22" height="22" style="animation:drift 9.8s linear infinite .9s"/>
      <use href="#petal" x="380"  y="-36" width="28" height="28" style="animation:drift 10.8s linear infinite .5s"/>
      <use href="#petal" x="260"  y="-30" width="24" height="24" style="animation:drift 9.7s linear infinite 1.3s"/>
      <use href="#petal" x="140"  y="-38" width="26" height="26" style="animation:drift 11.2s linear infinite .1s"/>
    </g>
  </svg>
</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=7DD3FC&center=true&vCenter=true&width=720&lines=Otaku+Dev+%E2%98%86+React%2FNext.js+%2F+Tailwind;Building+anime-inspired+web+experiences;Learning+every+day+%F0%9F%8C%9A" alt="typing animation" />
</p>

---

### 💫 About Me
I'm an 18-year-old student who enjoys exploring the world of programming.  
I love *thinking, designing, and building new projects* that continuously improve my skills.  
What excites me the most is making different parts of code work together —  
like connecting the *frontend* and *backend* into one seamless system.  

Right now, I’m focusing on *creating professional, visually beautiful front-end designs*  
and pushing myself until I can turn everything I imagine into real, working projects 💻💭  

---

### ⚡ Tech Stack & Tools
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,typescript,python,fastapi,figma,sqlite" />
</p>

- ⚛️ *Frontend:* React, Next.js, TailwindCSS, React Query  
- 🧠 *Backend:* FastAPI, SQLAlchemy  
- 🎨 *Design:* Figma  
- 🐍 *Languages:* TypeScript, Python  

---

### 🌸 Featured Project
✨ *My Personal Portfolio Website*  
🖥️ [supavich.vercel.app](https://supavich.vercel.app/)  
A clean anime-inspired personal portfolio built with **Next.js + TailwindCSS**,  
showcasing my projects, creativity, and coding journey.  


---

### 🧩 Fun Facts
- 💻 I spend most of my free time coding or designing something new  
- 🌙 I’m an *otaku* who loves anime and manga — they inspire my creativity  
- 🤝 I enjoy *teamwork* because it helps me learn and grow faster  
- 🎯 My goal: to become a *Software Engineer* who builds meaningful and fun digital experiences  

---

### 🌐 Connect with Me
📧 *Email:* 24.supavich@gmail.com  
📘 *Facebook:* [Kaw'su Thin'Shin](https://www.facebook.com/Kaw.su.Thin.Shin)  
📸 *Instagram:* [@kaw.suvaz](https://www.instagram.com/kaw.suvaz)

---

### ✨ GitHub Stats & Activity


---

### 🌸 Quote I Live By
*“Code is like art — each line expresses a part of who we are.”*  
— Kaw 🌙  
 

---

<p align="center">
  <img src="https://i.pinimg.com/originals/58/88/f7/5888f73a1b7f2e622013e6e20c38938d.gif" width="200"/>
</p>
