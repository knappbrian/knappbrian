<!-- GitHub Profile README — Brian Knapp -->
<!-- Wordle-style animated banner + Mermaid skills mindmap + stats -->

<p align="center">
  <!-- Inline, responsive SVG banner (tiles scale with container) -->
  <svg xmlns="http://www.w3.org/2000/svg" width="100%" viewBox="0 0 1200 340" role="img" aria-label="Wordle-style banner of Brian's skills">
    <defs>
      <style>
        .bg { fill: #0b1220; }
        .tile { fill: #111827; stroke: #1f2937; stroke-width: 4; rx: 18; ry: 18; }
        .green { fill: #22c55e; }
        .yellow { fill: #f59e0b; }
        .text { font-family: system-ui,-apple-system,Segoe UI,Roboto,Arial; fill: #e5e7eb; font-weight: 800; letter-spacing: 1px; }
        .label { font-size: 24px; fill: #9ca3af; font-weight: 600; }
        .word { font-size: 44px; text-anchor: middle; dominant-baseline: middle; }

        /* Fade cycle per word */
        @keyframes fade { 0%, 10% {opacity:1} 16.6%, 100% {opacity:0} }
        /* Each word in a tile uses the same duration but staggered start times to cycle */
        .t1 { animation: fade 18s infinite; animation-delay: 0s; }
        .t2 { animation: fade 18s infinite; animation-delay: 3s; }
        .t3 { animation: fade 18s infinite; animation-delay: 6s; }
        .t4 { animation: fade 18s infinite; animation-delay: 9s; }
        .t5 { animation: fade 18s infinite; animation-delay: 12s; }
        .t6 { animation: fade 18s infinite; animation-delay: 15s; }

        /* Keep tiles spaced — row of five, with gutter */
        .row { transform: translate(60px,100px); }
        .col1 { transform: translate(0px,0); }
        .col2 { transform: translate(220px,0); }
        .col3 { transform: translate(440px,0); }
        .col4 { transform: translate(660px,0); }
        .col5 { transform: translate(880px,0); }
      </style>
    </defs>

    <rect class="bg" x="0" y="0" width="1200" height="340" rx="24" ry="24"/>
    <text x="60" y="64" class="label">ECONOMICS • DATA ANALYSIS & VIZ • BUSINESS & RISK • MILITARY LEADERSHIP</text>

    <g class="row">
      <!-- Tile 1: Economics -->
      <g class="col1">
        <rect class="tile" x="0" y="0" width="200" height="180"/>
        <g transform="translate(100,90)">
          <text class="text word t1">ECONOMICS</text>
          <text class="text word t2">ECONOMETRICS</text>
          <text class="text word t3">MICRO</text>
          <text class="text word t4">MACRO</text>
          <text class="text word t5">FINANCIAL</text>
          <text class="text word t6">ANALYSIS</text>
        </g>
      </g>

      <!-- Tile 2: Data Analysis & Viz -->
      <g class="col2">
        <rect class="tile green" x="0" y="0" width="200" height="180"/>
        <g transform="translate(100,90)">
          <text class="text word t1">R / RSTUDIO</text>
          <text class="text word t2">STATA</text>
          <text class="text word t3">TABLEAU</text>
          <text class="text word t4">D3.JS</text>
          <text class="text word t5">POWER&nbsp;BI</text>
          <text class="text word t6">EXCEL</text>
        </g>
      </g>

      <!-- Tile 3: Communication & Viz tools -->
      <g class="col3">
        <rect class="tile" x="0" y="0" width="200" height="180"/>
        <g transform="translate(100,90)">
          <text class="text word t1">POWERPOINT</text>
          <text class="text word t2">SLIDE&nbsp;DECKS</text>
          <text class="text word t3">PITCH&nbsp;DECKS</text>
          <text class="text word t4">DATA&nbsp;VIZ</text>
          <text class="text word t5">STORYTELL</text>
          <text class="text word t6">COMMUNICATION</text>
        </g>
      </g>

      <!-- Tile 4: Military -->
      <g class="col4">
        <rect class="tile yellow" x="0" y="0" width="200" height="180"/>
        <g transform="translate(100,90)">
          <text class="text word t1">LEADERSHIP</text>
          <text class="text word t2">PROJECT&nbsp;MGMT</text>
          <text class="text word t3">STRATEGIC</text>
          <text class="text word t4">PLANNING</text>
          <text class="text word t5">OPERATIONS</text>
          <text class="text word t6">TEAMWORK</text>
        </g>
      </g>

      <!-- Tile 5: Business & Risk -->
      <g class="col5">
        <rect class="tile" x="0" y="0" width="200" height="180"/>
        <g transform="translate(100,90)">
          <text class="text word t1">DUE&nbsp;DILIGENCE</text>
          <text class="text word t2">THREAT&nbsp;MAPPING</text>
          <text class="text word t3">BCP</text>
          <text class="text word t4">STAKEHOLDER</text>
          <text class="text word t5">COMMS</text>
          <text class="text word t6">RISK</text>
        </g>
      </g>
    </g>
  </svg>
</p>

<h1 align="center">Hey 👋, I'm Brian</h1>
<h3 align="center">Strategy consultant with expertise in Economics, Data Analytics, and Business Intelligence</h3>

- 👨‍💻 Projects: <a href="https://knappbrian.github.io">knappbrian.github.io</a>

---

### Skills Mindmap (Mermaid)

```mermaid
%%{init: {"theme":"dark"}}%%
mindmap
  root((Skills))
    Domain Expertise
      Economics
        Microeconomics
        Macroeconomics
        Econometrics
        Financial Analysis
      Military
        Leadership
        Project Management
        Strategic Planning
        Operations
    Technical Skills
      Data Analysis & Viz
        R / RStudio
        STATA
        Excel
        PowerPoint
        Tableau
        D3.js
        Power BI
    Business & Risk
      Tech Due Diligence
      Control / Threat Mapping
      Stakeholder Communication
      Business Continuity (BCP)


<p align="center"> <img height="165" src="https://github-readme-stats.vercel.app/api?username=knappbrian&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats for knappbrian"/> <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=knappbrian&layout=compact&theme=radical&hide_border=true" alt="Top Languages for knappbrian"/> </p> <p align="center"> <img height="165" src="https://streak-stats.demolab.com?user=knappbrian&theme=radical&hide_border=true" alt="GitHub Streak for knappbrian"/> </p>
