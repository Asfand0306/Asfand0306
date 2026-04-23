<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      .bg  { fill: #0d1117; }
      .box { fill: none; stroke: #00ff9d; stroke-width: 1; opacity: 0.5; }
      .grn { fill: #00ff9d; font-family: 'Courier New', monospace; }
      .dim { fill: #00884d; font-family: 'Courier New', monospace; }
      .corner { fill: #00ff9d; }

      .blink { animation: blink 1.1s step-end infinite; }
      @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

      .scanline {
        stroke: #00ff9d;
        stroke-width: 100;
        stroke-opacity: 0.025;
        animation: scan 5s linear infinite;
      }
      @keyframes scan {
        0%   { transform: translateY(-100px); }
        100% { transform: translateY(300px); }
      }

      .f1 { animation: fadeIn 0.6s ease-out 0.1s both; }
      .f2 { animation: fadeIn 0.6s ease-out 0.4s both; }
      .f3 { animation: fadeIn 0.6s ease-out 0.7s both; }
      .f4 { animation: fadeIn 0.6s ease-out 1.0s both; }
      .f5 { animation: fadeIn 0.6s ease-out 1.3s both; }
      .f6 { animation: fadeIn 0.6s ease-out 1.6s both; }
      .f7 { animation: fadeIn 0.6s ease-out 1.9s both; }
      .f8 { animation: fadeIn 0.6s ease-out 2.2s both; }
      @keyframes fadeIn { from { opacity:0; } to { opacity:1; } }

      .pulse { animation: pulse 2.5s ease-in-out infinite; }
      @keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.3} }
    </style>
  </defs>

  <!-- Background -->
  <rect class="bg" width="860" height="200"/>

  <!-- Scanline -->
  <line class="scanline" x1="0" y1="0" x2="860" y2="0"/>

  <!-- Outer border -->
  <rect class="box f1" x="8" y="8" width="844" height="184" rx="1"/>

  <!-- Corner ticks -->
  <rect class="corner f1" x="8"  y="8"   width="16" height="2"/>
  <rect class="corner f1" x="8"  y="8"   width="2"  height="16"/>
  <rect class="corner f1" x="836" y="8"  width="16" height="2"/>
  <rect class="corner f1" x="850" y="8"  width="2"  height="16"/>
  <rect class="corner f1" x="8"  y="190" width="16" height="2"/>
  <rect class="corner f1" x="8"  y="174" width="2"  height="18"/>
  <rect class="corner f1" x="836" y="190" width="16" height="2"/>
  <rect class="corner f1" x="850" y="174" width="2"  height="18"/>

  <!-- Top status bar -->
  <text class="dim f1" x="24" y="23" font-size="11" letter-spacing="1">◈  CODEC SYSTEM — ACTIVE</text>
  <text class="dim f1" x="640" y="23" font-size="11" letter-spacing="1">TRAINING: SAIT — SOFTWARE DEV</text>

  <!-- Divider under top bar -->
  <line class="box f1" x1="8" y1="30" x2="852" y2="30"/>

  <!-- Left panel: signal / channel display -->
  <text class="dim f2" x="24" y="54"  font-size="10" letter-spacing="1">CH. FREQ</text>
  <text class="grn f3" x="24" y="74"  font-size="22" letter-spacing="4" font-weight="bold">40·85</text>
  <text class="dim f3" x="24" y="90"  font-size="10" letter-spacing="1">◄  PTT · REN  ►</text>

  <!-- Vertical divider -->
  <line class="box f2" x1="140" y1="34" x2="140" y2="186"/>

  <!-- Center: role + status lines -->
  <text class="dim f3" x="158" y="54"  font-size="10" letter-spacing="2">ROLE</text>
  <text class="grn f4" x="200" y="54"  font-size="11" letter-spacing="1">Junior Software Developer</text>

  <text class="dim f4" x="158" y="74"  font-size="10" letter-spacing="2">LOC</text>
  <text class="grn f5" x="200" y="74"  font-size="11" letter-spacing="1">Alberta, Canada</text>

  <text class="dim f5" x="158" y="94"  font-size="10" letter-spacing="2">STACK</text>
  <text class="grn f6" x="200" y="94"  font-size="11" letter-spacing="1">React · Next.js · Node · Firebase · Azure</text>

  <text class="dim f6" x="158" y="114" font-size="10" letter-spacing="2">STATUS</text>
  <text class="grn f7" x="200" y="114" font-size="11" letter-spacing="1">● AVAILABLE FOR HIRE</text>

  <!-- Prompt line -->
  <text class="dim f7" x="158" y="148" font-size="11" letter-spacing="1">&gt;_</text>
  <text class="grn f8" x="178" y="148" font-size="11" letter-spacing="1">full-stack dev · ui/ux · open-source enthusiast</text>
  <text class="grn blink f8" x="610" y="148" font-size="11">█</text>

  <!-- Bottom bar -->
  <line class="box f7" x1="8" y1="158" x2="852" y2="158"/>
  <text class="dim f8" x="24" y="174" font-size="10" letter-spacing="1.5">PATCHING YOU THROUGH NOW  ·  STAND BY</text>

  <!-- Signal bars -->
  <rect class="corner pulse f2" x="806" y="168" width="4" height="6"  rx="1"/>
  <rect class="corner pulse f2" x="814" y="164" width="4" height="10" rx="1"/>
  <rect class="corner pulse f2" x="822" y="159" width="4" height="15" rx="1"/>
  <rect class="corner pulse f2" x="830" y="154" width="4" height="20" rx="1"/>
</svg>
<div align="center">
  <img src="./header.svg" width="100%" alt="Asfandyar Khan"/>
</div>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/%E2%97%88_CODEC_SYSTEM-ACTIVE-00ff9d?style=flat-square&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/LOCATION-Alberta%2C_Canada-00ff9d?style=flat-square&labelColor=0d1117"/>
  &nbsp;
  <img src="https://img.shields.io/badge/STATUS-Available_for_Hire-00ff9d?style=flat-square&labelColor=0d1117"/>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=Asfand0306&style=flat-square&color=00ff9d&labelColor=0d1117&label=VIEWS"/>
</p>

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

## `> LANGUAGES`

<p>
  <img src="https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/HTML5-0d1117?style=for-the-badge&logo=html5&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/CSS3-0d1117?style=for-the-badge&logo=css3&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=mysql&logoColor=00ff9d"/>
</p>

## `> FRAMEWORKS & LIBRARIES`

<p>
  <img src="https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Next.js-0d1117?style=for-the-badge&logo=nextdotjs&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=nodedotjs&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/npm-0d1117?style=for-the-badge&logo=npm&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-0d1117?style=for-the-badge&logo=tailwindcss&logoColor=00ff9d"/>
</p>

## `> TOOLS & PLATFORMS`

<p>
  <img src="https://img.shields.io/badge/VS_Code-0d1117?style=for-the-badge&logo=visualstudiocode&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Eclipse-0d1117?style=for-the-badge&logo=eclipseide&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Figma-0d1117?style=for-the-badge&logo=figma&logoColor=00ff9d"/>
</p>

## `> CLOUD & DEPLOYMENT`

<p>
  <img src="https://img.shields.io/badge/Firebase-0d1117?style=for-the-badge&logo=firebase&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Azure-0d1117?style=for-the-badge&logo=microsoftazure&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Vercel-0d1117?style=for-the-badge&logo=vercel&logoColor=00ff9d"/>
  <img src="https://img.shields.io/badge/Supabase-0d1117?style=for-the-badge&logo=supabase&logoColor=00ff9d"/>
</p>

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

## `> GITHUB STATS`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Asfand0306&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00ff9d&icon_color=00ff9d&text_color=00cc7a" width="49%"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Asfand0306&hide_border=true&background=0d1117&ring=00ff9d&fire=00ff9d&currStreakLabel=00ff9d&sideLabels=00cc7a&sideNums=00ff9d&dates=00cc7a" width="49%"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Asfand0306&layout=compact&hide_border=true&bg_color=0d1117&title_color=00ff9d&text_color=00cc7a"/>
</p>

## `> ACTIVITY`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Asfand0306&bg_color=0d1117&color=00ff9d&line=00ff9d&point=00ff9d&area=true&area_color=00ff9d&hide_border=true" width="100%"/>
</p>

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

</div>

## `> CONNECT`

<p align="center">
  <a href="https://www.linkedin.com/in/asfand-khan-7a8a971aa/">
    <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=00ff9d"/>
  </a>
  <a href="mailto:Asfand0306@gmail.com">
    <img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00ff9d"/>
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Portfolio-Coming_Soon-0d1117?style=for-the-badge&logo=vercel&logoColor=00ff9d"/>
  </a>
</p>

<div align="center">

```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<sub>⭐️ From <a href="https://github.com/Asfand0306">Asfand0306</a></sub>

</div>
