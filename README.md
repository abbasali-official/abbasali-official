<!-- Profile repository: AbbasAli-official/AbbasAli-official (must be PUBLIC) -->

<!-- ═══════════════ HERO / HEADER ═══════════════ -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 400" width="1200" height="400" role="img" aria-labelledby="t d">
  <title id="t">Abbas Ali - AI Graduate</title>
  <desc id="d">Profile banner: Abbas Ali, AI Graduate, with a typing animation of Artificial Intelligence, Machine Learning, Computer Vision and Generative AI, beside an AI chip illustration.</desc>

  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#0B1F3A"/><stop offset=".6" stop-color="#0A1830"/><stop offset="1" stop-color="#06101F"/>
    </linearGradient>
    <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#00B8D9"/><stop offset="1" stop-color="#7C9CFF"/>
    </linearGradient>
    <linearGradient id="die" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#12386A"/><stop offset="1" stop-color="#0A1D3A"/>
    </linearGradient>
    <radialGradient id="glow" cx=".5" cy=".5" r=".5">
      <stop offset="0" stop-color="#00B8D9" stop-opacity=".30"/><stop offset="1" stop-color="#00B8D9" stop-opacity="0"/>
    </radialGradient>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0H0V40" fill="none" stroke="#fff" stroke-opacity=".045"/>
    </pattern>
    <clipPath id="card"><rect width="1200" height="400" rx="20"/></clipPath>
    <clipPath id="cp0"><rect class="tw0" x="100" y="262" width="0" height="48"/></clipPath>
    <clipPath id="cp1"><rect class="tw1" x="100" y="262" width="0" height="48"/></clipPath>
    <clipPath id="cp2"><rect class="tw2" x="100" y="262" width="0" height="48"/></clipPath>
    <clipPath id="cp3"><rect class="tw3" x="100" y="262" width="0" height="48"/></clipPath>
  </defs>

  <style>
    text { font-family:'Segoe UI','Poppins','Helvetica Neue',Arial,sans-serif; }
    .name { fill:#fff; font-size:84px; font-weight:700; letter-spacing:-1.5px; }
    .sub  { fill:#C9D6EA; font-size:30px; font-weight:500; letter-spacing:6px; }
    .type { fill:#00B8D9; font-size:28px; font-weight:600; font-family:'JetBrains Mono','Fira Code',Consolas,'SF Mono','Courier New',monospace; }
    .prompt { fill:#7C9CFF; font-size:28px; font-weight:700; font-family:Consolas,'Courier New',monospace; }
    .cur  { fill:#fff; animation:blink 1s steps(1) infinite; }

    .mesh line { stroke:#00B8D9; stroke-opacity:.14; stroke-width:1; }
    .mesh circle { fill:#00B8D9; fill-opacity:.5; animation:twinkle 4s ease-in-out infinite; }
    .ring  { fill:none; stroke:#00B8D9; stroke-opacity:.28; stroke-dasharray:2 8; transform-origin:930px 200px; }
    .r1 { animation:spin 60s linear infinite; }
    .r2 { animation:spin 90s linear infinite reverse; stroke-opacity:.18; }
    .aura { transform-box:fill-box; transform-origin:center; animation:breathe 5s ease-in-out infinite; }
    .pins line { stroke:#00B8D9; stroke-width:3; stroke-linecap:round; stroke-opacity:.85; }
    .trace { fill:none; stroke:#00B8D9; stroke-opacity:.7; stroke-width:1.5; stroke-dasharray:4 6; animation:flow 3s linear infinite; }
    .die  { fill:url(#die); stroke:#00B8D9; stroke-width:2; }
    .die2 { fill:none; stroke:#00B8D9; stroke-opacity:.35; }
    .ai   { fill:#fff; font-size:58px; font-weight:800; letter-spacing:2px; }
    .bd   { fill:#0B1F3A; stroke:#00B8D9; stroke-opacity:.7; stroke-width:1.5; }
    .ic   { fill:none; stroke:#7FE3F5; stroke-width:2; stroke-linecap:round; stroke-linejoin:round; }
    .icf  { fill:#7FE3F5; }
    .badge { animation:float 6s ease-in-out infinite; }

    .rise { opacity:0; animation:rise .9s cubic-bezier(.2,.7,.2,1) forwards; }
    .d1 { animation-delay:.1s } .d2 { animation-delay:.35s } .d3 { animation-delay:.6s }
    .bar  { transform-box:fill-box; transform-origin:left center; transform:scaleX(0); animation:grow 1s .55s cubic-bezier(.2,.7,.2,1) forwards; }

    .tw0{animation:tw0 20s infinite} .cu0{animation:cu0 20s infinite}
    .tw1{animation:tw1 20s infinite} .cu1{animation:cu1 20s infinite}
    .tw2{animation:tw2 20s infinite} .cu2{animation:cu2 20s infinite}
    .tw3{animation:tw3 20s infinite} .cu3{animation:cu3 20s infinite}

    @keyframes blink   { 0%,50% { opacity:1 } 50.01%,100% { opacity:0 } }
    @keyframes spin    { to { transform:rotate(360deg) } }
    @keyframes flow    { to { stroke-dashoffset:-40 } }
    @keyframes twinkle { 0%,100% { fill-opacity:.2 } 50% { fill-opacity:.9 } }
    @keyframes breathe { 0%,100% { transform:scale(.9); opacity:.7 } 50% { transform:scale(1.08); opacity:1 } }
    @keyframes float   { 0%,100% { transform:translateY(0) } 50% { transform:translateY(-8px) } }
    @keyframes rise    { from { opacity:0; transform:translateY(14px) } to { opacity:1; transform:none } }
    @keyframes grow    { to { transform:scaleX(1) } }

    /* typing: clip width (tw) + cursor position (cu), one phrase every 5s of a 20s loop */
    @keyframes tw0{0%{width:0;animation-timing-function:steps(23,end)} 9%{width:391px} 18%{width:391px;animation-timing-function:steps(23,end)} 23%{width:0} 100%{width:0}}
    @keyframes cu0{0%{opacity:1;transform:translateX(0);animation-timing-function:steps(23,end)} 9%{opacity:1;transform:translateX(391px)} 18%{opacity:1;transform:translateX(391px);animation-timing-function:steps(23,end)} 23%{opacity:1;transform:translateX(0)} 23.5%{opacity:0;transform:translateX(0)} 100%{opacity:0}}
    @keyframes tw1{0%{width:0} 25%{width:0;animation-timing-function:steps(16,end)} 34%{width:272px} 43%{width:272px;animation-timing-function:steps(16,end)} 48%{width:0} 100%{width:0}}
    @keyframes cu1{0%{opacity:0;transform:translateX(0)} 24.99%{opacity:0;transform:translateX(0)} 25%{opacity:1;transform:translateX(0);animation-timing-function:steps(16,end)} 34%{opacity:1;transform:translateX(272px)} 43%{opacity:1;transform:translateX(272px);animation-timing-function:steps(16,end)} 48%{opacity:1;transform:translateX(0)} 48.5%{opacity:0;transform:translateX(0)} 100%{opacity:0}}
    @keyframes tw2{0%{width:0} 50%{width:0;animation-timing-function:steps(15,end)} 59%{width:255px} 68%{width:255px;animation-timing-function:steps(15,end)} 73%{width:0} 100%{width:0}}
    @keyframes cu2{0%{opacity:0;transform:translateX(0)} 49.99%{opacity:0;transform:translateX(0)} 50%{opacity:1;transform:translateX(0);animation-timing-function:steps(15,end)} 59%{opacity:1;transform:translateX(255px)} 68%{opacity:1;transform:translateX(255px);animation-timing-function:steps(15,end)} 73%{opacity:1;transform:translateX(0)} 73.5%{opacity:0;transform:translateX(0)} 100%{opacity:0}}
    @keyframes tw3{0%{width:0} 75%{width:0;animation-timing-function:steps(13,end)} 84%{width:221px} 93%{width:221px;animation-timing-function:steps(13,end)} 98%{width:0} 100%{width:0}}
    @keyframes cu3{0%{opacity:0;transform:translateX(0)} 74.99%{opacity:0;transform:translateX(0)} 75%{opacity:1;transform:translateX(0);animation-timing-function:steps(13,end)} 84%{opacity:1;transform:translateX(221px)} 93%{opacity:1;transform:translateX(221px);animation-timing-function:steps(13,end)} 98%{opacity:1;transform:translateX(0)} 98.5%{opacity:0;transform:translateX(0)} 100%{opacity:0}}

    @media (prefers-reduced-motion: reduce) {
      * { animation:none !important; }
      .rise { opacity:1; } .bar { transform:none; }
      .tw0 { width:391px; }
      .cur { opacity:0; }
    }
  </style>

  <g clip-path="url(#card)">
    <rect width="1200" height="400" fill="url(#bg)"/>
    <rect width="1200" height="400" fill="url(#grid)"/>
    <circle cx="930" cy="200" r="300" fill="url(#glow)" class="aura"/>
    <circle cx="90" cy="430" r="240" fill="url(#glow)" opacity=".45"/>

    <!-- AI theme: neural mesh, rings, chip, concept icons -->
    <g class="mesh">
      <line x1="690" y1="60" x2="740" y2="150"/>
      <line x1="690" y1="60" x2="820" y2="40"/>
      <line x1="690" y1="60" x2="660" y2="150"/>
      <line x1="740" y1="150" x2="700" y2="250"/>
      <line x1="740" y1="150" x2="820" y2="40"/>
      <line x1="740" y1="150" x2="660" y2="150"/>
      <line x1="700" y1="250" x2="760" y2="340"/>
      <line x1="700" y1="250" x2="700" y2="370"/>
      <line x1="700" y1="250" x2="660" y2="150"/>
      <line x1="760" y1="340" x2="900" y2="372"/>
      <line x1="760" y1="340" x2="700" y2="370"/>
      <line x1="1060" y1="40" x2="1120" y2="110"/>
      <line x1="1120" y1="110" x2="1150" y2="210"/>
      <line x1="1150" y1="210" x2="1110" y2="300"/>
      <line x1="1150" y1="210" x2="1170" y2="350"/>
      <line x1="1110" y1="300" x2="1040" y2="355"/>
      <line x1="1110" y1="300" x2="1170" y2="350"/>
      <line x1="1040" y1="355" x2="900" y2="372"/>
      <line x1="1040" y1="355" x2="1170" y2="350"/>
      <circle cx="690" cy="60" r="2.6" style="animation-delay:-0.0s"/>
      <circle cx="740" cy="150" r="2.6" style="animation-delay:-0.7s"/>
      <circle cx="700" cy="250" r="2.6" style="animation-delay:-1.4s"/>
      <circle cx="760" cy="340" r="2.6" style="animation-delay:-2.1s"/>
      <circle cx="820" cy="40" r="2.6" style="animation-delay:-2.8s"/>
      <circle cx="1060" cy="40" r="2.6" style="animation-delay:-3.5s"/>
      <circle cx="1120" cy="110" r="2.6" style="animation-delay:-0.2s"/>
      <circle cx="1150" cy="210" r="2.6" style="animation-delay:-0.9s"/>
      <circle cx="1110" cy="300" r="2.6" style="animation-delay:-1.6s"/>
      <circle cx="1040" cy="355" r="2.6" style="animation-delay:-2.3s"/>
      <circle cx="900" cy="372" r="2.6" style="animation-delay:-3.0s"/>
      <circle cx="700" cy="370" r="2.6" style="animation-delay:-3.7s"/>
      <circle cx="1170" cy="350" r="2.6" style="animation-delay:-0.4s"/>
      <circle cx="660" cy="150" r="2.6" style="animation-delay:-1.1s"/>
    </g>
    <circle class="ring r1" cx="930" cy="200" r="172" stroke-width="1.6"/>
    <circle class="ring r2" cx="930" cy="200" r="222" stroke-width="1.2"/>

    <!-- chip circuit traces -->
    <g>
      <polyline class="trace" style="animation-delay:-0.0s" points="846,152 818,152 802,136"/>
      <polyline class="trace" style="animation-delay:-0.3s" points="1014,152 1042,152 1058,136"/>
      <polyline class="trace" style="animation-delay:-0.9s" points="882,116 882,94 868,80"/>
      <polyline class="trace" style="animation-delay:-1.2s" points="882,284 882,306 868,320"/>
      <polyline class="trace" style="animation-delay:-0.6s" points="846,176 804,176 788,160"/>
      <polyline class="trace" style="animation-delay:-0.9s" points="1014,176 1056,176 1072,160"/>
      <polyline class="trace" style="animation-delay:-1.5s" points="906,116 906,80 892,66"/>
      <polyline class="trace" style="animation-delay:-1.8s" points="906,284 906,320 892,334"/>
      <polyline class="trace" style="animation-delay:-1.2s" points="846,200 818,200 802,184"/>
      <polyline class="trace" style="animation-delay:-1.5s" points="1014,200 1042,200 1058,216"/>
      <polyline class="trace" style="animation-delay:-2.1s" points="930,116 930,94 916,80"/>
      <polyline class="trace" style="animation-delay:-2.4s" points="930,284 930,306 944,320"/>
      <polyline class="trace" style="animation-delay:-1.8s" points="846,224 804,224 788,240"/>
      <polyline class="trace" style="animation-delay:-2.1s" points="1014,224 1056,224 1072,240"/>
      <polyline class="trace" style="animation-delay:-2.7s" points="954,116 954,80 968,66"/>
      <polyline class="trace" style="animation-delay:-3.0s" points="954,284 954,320 968,334"/>
      <polyline class="trace" style="animation-delay:-2.4s" points="846,248 818,248 802,264"/>
      <polyline class="trace" style="animation-delay:-2.7s" points="1014,248 1042,248 1058,264"/>
      <polyline class="trace" style="animation-delay:-3.3s" points="978,116 978,94 992,80"/>
      <polyline class="trace" style="animation-delay:-3.6s" points="978,284 978,306 992,320"/>
    </g>

    <!-- chip pins -->
    <g class="pins">
      <line x1="846" y1="152" x2="860" y2="152"/>
      <line x1="1000" y1="152" x2="1014" y2="152"/>
      <line x1="882" y1="116" x2="882" y2="130"/>
      <line x1="882" y1="270" x2="882" y2="284"/>
      <line x1="846" y1="176" x2="860" y2="176"/>
      <line x1="1000" y1="176" x2="1014" y2="176"/>
      <line x1="906" y1="116" x2="906" y2="130"/>
      <line x1="906" y1="270" x2="906" y2="284"/>
      <line x1="846" y1="200" x2="860" y2="200"/>
      <line x1="1000" y1="200" x2="1014" y2="200"/>
      <line x1="930" y1="116" x2="930" y2="130"/>
      <line x1="930" y1="270" x2="930" y2="284"/>
      <line x1="846" y1="224" x2="860" y2="224"/>
      <line x1="1000" y1="224" x2="1014" y2="224"/>
      <line x1="954" y1="116" x2="954" y2="130"/>
      <line x1="954" y1="270" x2="954" y2="284"/>
      <line x1="846" y1="248" x2="860" y2="248"/>
      <line x1="1000" y1="248" x2="1014" y2="248"/>
      <line x1="978" y1="116" x2="978" y2="130"/>
      <line x1="978" y1="270" x2="978" y2="284"/>
    </g>

    <!-- chip body -->
    <rect class="die" x="860" y="130" width="140" height="140" rx="20"/>
    <rect class="die2" x="872" y="142" width="116" height="116" rx="12"/>
    <text class="ai" x="930" y="220" text-anchor="middle">AI</text>

    <!-- concept icons: eye (vision), sparkle (generative), graph (ML), layers (deep learning) -->
    <g transform="translate(1036,64)"><g class="badge" style="animation-delay:-0.0s"><circle r="27" class="bd"/><path d="M-14 0Q0 -12 14 0Q0 12 -14 0Z" class="ic"/><circle r="4.2" class="icf"/></g></g>
    <g transform="translate(1089,264)"><g class="badge" style="animation-delay:-1.8s"><circle r="27" class="bd"/><path d="M0 -13C2 -4 4 -2 13 0C4 2 2 4 0 13C-2 4 -4 2 -13 0C-4 -2 -2 -4 0 -13Z" class="icf"/></g></g>
    <g transform="translate(824,336)"><g class="badge" style="animation-delay:-3.6s"><circle r="27" class="bd"/><g class="ic"><line x1="-10" y1="8" x2="0" y2="-9"/><line x1="0" y1="-9" x2="10" y2="8"/><line x1="-10" y1="8" x2="10" y2="8"/></g><circle cx="-10" cy="8" r="3.2" class="icf"/><circle cx="0" cy="-9" r="3.2" class="icf"/><circle cx="10" cy="8" r="3.2" class="icf"/></g></g>
    <g transform="translate(784,109)"><g class="badge" style="animation-delay:-5.4s"><circle r="27" class="bd"/><path d="M-13 -5L0 -12L13 -5L0 2Z" class="ic"/><path d="M-13 2L0 9L13 2" class="ic"/><path d="M-13 8L0 15L13 8" class="ic" opacity=".6"/></g></g>

    <!-- Text: 1) name  2) subtitle  3) typing -->
    <g class="rise d1"><text class="name" x="66" y="150">Abbas Ali</text></g>
    <rect class="bar" x="70" y="174" width="120" height="4" rx="2" fill="url(#accent)"/>
    <g class="rise d2"><text class="sub" x="70" y="226">AI GRADUATE</text></g>
    <g class="rise d3">
      <text class="prompt" x="68" y="296">&gt;</text>
      <text class="type" x="100" y="296" textLength="391" lengthAdjust="spacing" clip-path="url(#cp0)">Artificial Intelligence</text>
      <text class="type" x="100" y="296" textLength="272" lengthAdjust="spacing" clip-path="url(#cp1)">Machine Learning</text>
      <text class="type" x="100" y="296" textLength="255" lengthAdjust="spacing" clip-path="url(#cp2)">Computer Vision</text>
      <text class="type" x="100" y="296" textLength="221" lengthAdjust="spacing" clip-path="url(#cp3)">Generative AI</text>
      <g class="cu0" opacity="0"><rect class="cur" x="102" y="268" width="3" height="34" rx="1.5"/></g>
      <g class="cu1" opacity="0"><rect class="cur" x="102" y="268" width="3" height="34" rx="1.5"/></g>
      <g class="cu2" opacity="0"><rect class="cur" x="102" y="268" width="3" height="34" rx="1.5"/></g>
      <g class="cu3" opacity="0"><rect class="cur" x="102" y="268" width="3" height="34" rx="1.5"/></g>
    </g>

    <rect x=".5" y=".5" width="1199" height="399" rx="19.5" fill="none" stroke="#00B8D9" stroke-opacity=".25"/>
  </g>
</svg>

<br/>

<!-- ═══════════════ ACADEMIC PROFILE ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=520&height=45&lines=Academic+Profile" alt="Academic Profile" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<p align="justify">
I am an <strong>Artificial Intelligence graduate</strong> from <strong>The Islamia University of Bahawalpur (IUB), Pakistan</strong>, with a <strong>CGPA of 3.59/4.00</strong>. My academic foundation includes Artificial Intelligence, Machine Learning, Deep Learning, and Computer Vision. My technical interests span <strong>Machine Learning, Deep Learning, Computer Vision, and Generative AI</strong>, with a focus on developing deeper technical expertise and exploring practical AI applications.
<br/><br/>
Alongside my studies, I have served the <strong>Baltikhar Students Organisation (BSO)</strong> as Education Secretary and Media Secretary, and currently serve as Publication Head, building experience in student coordination, organisational communication, and community engagement. I am now focused on pursuing <strong>postgraduate studies and research in Artificial Intelligence</strong>, with the long-term objective of contributing to practical AI solutions through advanced study and research.
</p>

<br/>

<!-- ═══════════════ RESEARCH INTERESTS ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=520&height=45&lines=Research+Interests" alt="Research Interests" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<div align="center">

| 🧠 Artificial Intelligence | ✨ Generative AI | 📊 Machine Learning |
|:---:|:---:|:---:|
| **👁️ Computer Vision** | **🔬 Deep Learning** | **⚙️ Intelligent Systems** |

</div>

<br/>

<!-- ═══════════════ TECHNICAL SKILLS ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=520&height=45&lines=Technical+Skills" alt="Technical Skills" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<div align="center">

| Domain | Tools & Technologies |
|:--|:--|
| **Programming** | <img src="https://img.shields.io/badge/Python-0B1F3A?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/> <img src="https://img.shields.io/badge/HTML5-0B1F3A?style=flat-square&logo=html5&logoColor=E34F26" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS3-0B1F3A?style=flat-square&logo=css3&logoColor=1572B6" alt="CSS3"/> <img src="https://img.shields.io/badge/SQL-0B1F3A?style=flat-square&logo=postgresql&logoColor=4169E1" alt="SQL"/> |
| **Machine & Deep Learning** | <img src="https://img.shields.io/badge/PyTorch-0B1F3A?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch"/> <img src="https://img.shields.io/badge/TensorFlow-0B1F3A?style=flat-square&logo=tensorflow&logoColor=FF6F00" alt="TensorFlow"/> <img src="https://img.shields.io/badge/Scikit--learn-0B1F3A?style=flat-square&logo=scikitlearn&logoColor=F7931E" alt="Scikit-learn"/> <img src="https://img.shields.io/badge/Keras-0B1F3A?style=flat-square&logo=keras&logoColor=D00000" alt="Keras"/> |
| **Computer Vision** | <img src="https://img.shields.io/badge/OpenCV-0B1F3A?style=flat-square&logo=opencv&logoColor=5C3EE8" alt="OpenCV"/> <img src="https://img.shields.io/badge/CNNs-0B1F3A?style=flat-square" alt="CNNs"/> <img src="https://img.shields.io/badge/Image_Classification-0B1F3A?style=flat-square" alt="Image Classification"/> |
| **Data Science** | <img src="https://img.shields.io/badge/Pandas-0B1F3A?style=flat-square&logo=pandas&logoColor=150458" alt="Pandas"/> <img src="https://img.shields.io/badge/NumPy-0B1F3A?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy"/> <img src="https://img.shields.io/badge/Matplotlib-0B1F3A?style=flat-square&logo=plotly&logoColor=3F4F75" alt="Matplotlib"/> <img src="https://img.shields.io/badge/EDA-0B1F3A?style=flat-square" alt="Exploratory Data Analysis"/> |
| **Web Development** | <img src="https://img.shields.io/badge/React-0B1F3A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/TypeScript-0B1F3A?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"/> <img src="https://img.shields.io/badge/Supabase-0B1F3A?style=flat-square&logo=supabase&logoColor=3FCF8E" alt="Supabase"/> |
| **Development Tools** | <img src="https://img.shields.io/badge/Git-0B1F3A?style=flat-square&logo=git&logoColor=F05032" alt="Git"/> <img src="https://img.shields.io/badge/GitHub-0B1F3A?style=flat-square&logo=github&logoColor=FFFFFF" alt="GitHub"/> <img src="https://img.shields.io/badge/VS_Code-0B1F3A?style=flat-square&logo=visualstudiocode&logoColor=007ACC" alt="VS Code"/> <img src="https://img.shields.io/badge/Jupyter-0B1F3A?style=flat-square&logo=jupyter&logoColor=F37626" alt="Jupyter"/> <img src="https://img.shields.io/badge/Google_Colab-0B1F3A?style=flat-square&logo=googlecolab&logoColor=F9AB00" alt="Google Colab"/> |

</div>

<br/>

<!-- ═══════════════ EDUCATION & CERTIFICATIONS ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=560&height=45&lines=Education+%26+Certifications" alt="Education and Certifications" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<div align="center">

| Qualification | Institution |
|:--|:--|
| 🎓 **BS in Artificial Intelligence** (CGPA 3.59 / 4.00) | The Islamia University of Bahawalpur |
| 📜 **Machine Learning with Python** | IBM / Coursera |
| 📜 **Python for Data Science and AI** | Coursera |
| 📜 **Artificial Intelligence on Microsoft Azure** | Microsoft |
| 📜 **Google AI Essentials** | Google |
| 📜 **Data Analysis with Python** | IBM / Cognitive Class |

</div>

<br/>

<!-- ═══════════════ HONORS & AWARDS ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=480&height=45&lines=Honors+%26+Awards" alt="Honors and Awards" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<div align="center">

| Recognition | Details |
|:--|:--|
| 🏅 **Prime Minister's Laptop Scheme** | Government of Pakistan, selected on academic merit |
| 🥉 **Third Position, University Class Project** | Awarded for a team project, Automatic Hand-Wash System |

</div>

<br/>

</div> <br/> <!-- ═══════════════ LEADERSHIP & COMMUNITY ═══════════════ --> <div align="center"> <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=560&height=45&lines=Leadership+%26+Community" alt="Leadership and Community" /> <br/> <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>

<br/><br/>

Baltikhar Students Organisation (BSO) <br/> <sub>📍 Skardu, Gilgit-Baltistan, Pakistan</sub>

| Position | Tenure | Key Responsibilities |
|:--|:--:|:--|
| **Publication Head** | Dec 2025 – Present | Leading publications, organizational communications, and educational content. |
| **Media Secretary** | Dec 2024 – Dec 2025 | Managing digital media, social media communications, and student engagement. |
| **Education Secretary** | Mar 2023 – Dec 2024 | Coordinating educational initiatives, academic activities, and student development programmes. |

</div>

<br/>

<!-- ═══════════════ GITHUB ACTIVITY ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=480&height=45&lines=GitHub+Activity" alt="GitHub Activity" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>
</div>

<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AbbasAli-official&bg_color=0D1117&color=C9D1D9&line=00B8D9&point=FFFFFF&area=true&area_color=00B8D9&hide_border=true">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=AbbasAli-official&bg_color=FFFFFF&color=334155&line=00B8D9&point=0B1F3A&area=true&area_color=00B8D9&hide_border=true">
  <img alt="Contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=AbbasAli-official&bg_color=FFFFFF&color=334155&line=00B8D9&point=0B1F3A&area=true&area_color=00B8D9&hide_border=true" width="95%">
</picture>
</div>

<br/>

<!-- ═══════════════ CONNECT ═══════════════ -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2500&pause=60000&color=00B8D9&center=true&vCenter=true&repeat=false&width=420&height=45&lines=Let's+Connect" alt="Let's Connect" />
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=rect&height=2&color=gradient&customColorList=12,20,24" width="40%" alt=""/>

<br/><br/>

<p align="center">
  Open to research collaborations, academic opportunities,<br/>
  and professional discussions in Artificial Intelligence.
</p>

<a href="mailto:AbbasAli.Eng26@gmail.com">
  <img src="https://img.shields.io/badge/Email-0B1F3A?style=for-the-badge&logo=gmail&logoColor=00B8D9" alt="Email" />
</a>
&nbsp;
<a href="https://linkedin.com/in/abbasali-aiengineer">
  <img src="https://img.shields.io/badge/LinkedIn-0B1F3A?style=for-the-badge&logo=linkedin&logoColor=00B8D9" alt="LinkedIn" />
</a>
&nbsp;
<a href="https://github.com/AbbasAli-official">
  <img src="https://img.shields.io/badge/GitHub-0B1F3A?style=for-the-badge&logo=github&logoColor=00B8D9" alt="GitHub" />
</a>

</div>

<!-- ═══════════════ FOOTER ═══════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=12,20,24&section=footer&reversal=true" width="100%" alt=""/>
