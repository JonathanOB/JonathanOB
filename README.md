<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0a0d0f&height=4&section=header" width="100%"/>

</div>

<!--  ============================================================
      GITHUB PROFILE — SVG HUD EDITION
      Drop this file into your <username>/<username> repo.
      The SVG is rendered natively by GitHub — no hosting needed.
      ============================================================ -->

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════╗
║  SYS.PROFILE  //  v2.0.26                    53.3498°N  6.2603°W  —  IE ║
╚══════════════════════════════════════════════════════════════════════════╝
```

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 860 620" width="860" height="620">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&amp;display=swap');
      .mono { font-family: 'Space Mono', 'Courier New', monospace; }
      .syne { font-family: 'Space Mono', 'Courier New', monospace; font-weight: 700; }
      @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }
      @keyframes dash  { to { stroke-dashoffset: -32; } }
      @keyframes fadein{ from{opacity:0} to{opacity:1} }
      .cursor { animation: blink 1.1s step-end infinite; }
      .flight { animation: dash 3s linear infinite; }
      .fadein { animation: fadein 1s ease both; }
    </style>
    <!-- scanline pattern -->
    <pattern id="scan" x="0" y="0" width="1" height="4" patternUnits="userSpaceOnUse">
      <rect width="1" height="4" fill="#0a0d0f"/>
      <rect y="3" width="1" height="1" fill="rgba(0,0,0,0.18)"/>
    </pattern>
    <!-- subtle grid -->
    <pattern id="grid" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40,0 L0,0 0,40" fill="none" stroke="rgba(74,186,112,0.04)" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- ── BACKGROUND ── -->
  <rect width="860" height="620" fill="#0a0d0f"/>
  <rect width="860" height="620" fill="url(#grid)"/>
  <rect width="860" height="620" fill="url(#scan)" opacity="0.6"/>

  <!-- ── OUTER BORDER ── -->
  <rect x="16" y="16" width="828" height="588" fill="none" stroke="rgba(74,186,112,0.2)" stroke-width="1"/>
  <!-- corner accents -->
  <polyline points="16,36 16,16 36,16"   fill="none" stroke="#4aba70" stroke-width="2"/>
  <polyline points="824,16 844,16 844,36" fill="none" stroke="#4aba70" stroke-width="2"/>
  <polyline points="16,584 16,604 36,604" fill="none" stroke="#4aba70" stroke-width="2"/>
  <polyline points="824,604 844,604 844,584" fill="none" stroke="#4aba70" stroke-width="2"/>

  <!-- ── SYS LABEL TOP ── -->
  <rect x="30" y="9" width="190" height="14" fill="#0a0d0f"/>
  <text x="36" y="20" class="mono" font-size="9" fill="#4aba70" letter-spacing="2">SYS.PROFILE // v2.0.26</text>

  <!-- ── CALLSIGN ── -->
  <text x="44" y="78" class="syne" font-size="38" fill="#e8f5e2" letter-spacing="-1">FULL STACK</text>
  <text x="44" y="120" class="syne" font-size="38" fill="#4aba70" letter-spacing="-1">DEVELOPER</text>
  <!-- blinking cursor -->
  <rect x="344" y="96" width="9" height="20" fill="#4aba70" class="cursor"/>

  <!-- tagline -->
  <text x="44" y="145" class="mono" font-size="10" fill="#4a7a4a" letter-spacing="3">◈  IRELAND  ·  AVIATION  ·  SECURITY  ·  CODE</text>
  <text x="44" y="161" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">53.3498° N, 6.2603° W  —  Dublin, IE</text>

  <!-- readout right -->
  <text x="730" y="65"  class="mono" font-size="22" fill="#4aba70" text-anchor="middle" font-weight="700">CPL</text>
  <text x="730" y="79"  class="mono" font-size="9"  fill="#3d6b3d" text-anchor="middle" letter-spacing="1">PILOT CERT.</text>
  <text x="800" y="65"  class="mono" font-size="22" fill="#4aba70" text-anchor="middle" font-weight="700">MSc</text>
  <text x="800" y="79"  class="mono" font-size="9"  fill="#3d6b3d" text-anchor="middle" letter-spacing="1">CYBERSEC.</text>
  <text x="765" y="115" class="mono" font-size="22" fill="#4aba70" text-anchor="middle" font-weight="700">BSc</text>
  <text x="765" y="129" class="mono" font-size="9"  fill="#3d6b3d" text-anchor="middle" letter-spacing="1">DEV &amp; C.S.</text>

  <!-- ── FLIGHT PATH ── -->
  <polyline
    points="44,178 100,178 120,168 165,175 220,160 285,172 350,163 430,170 510,155 590,167 650,158 730,169 775,162 820,162"
    fill="none" stroke="#4aba70" stroke-width="1.2"
    stroke-dasharray="8 4"
    class="flight"
  />
  <polygon points="820,162 813,158 813,166" fill="#4aba70"/>

  <!-- ── STATUS BAR ── -->
  <line x1="44" y1="188" x2="816" y2="188" stroke="rgba(74,186,112,0.15)" stroke-width="1"/>
  <circle cx="56"  cy="199" r="3" fill="#4aba70"/>
  <text   x="63"  y="203" class="mono" font-size="9" fill="#4aba70"  letter-spacing="1">AVAILABLE</text>
  <text   x="160" y="203" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">BUG BOUNTIES</text>
  <text   x="278" y="203" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">OPEN SOURCE</text>
  <text   x="392" y="203" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">AI RESEARCH</text>
  <text   x="496" y="203" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">SEO / DIGITAL MKT</text>
  <line x1="44" y1="210" x2="816" y2="210" stroke="rgba(74,186,112,0.15)" stroke-width="1"/>

  <!-- ══ SECTION: CREDENTIALS ══ -->
  <text x="44" y="235" class="mono" font-size="9" fill="#4aba70" letter-spacing="3">// CREDENTIALS &amp; CLEARANCES</text>
  <line x1="44" y1="240" x2="816" y2="240" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>

  <!-- CRED CELLS  (4 × equal width) -->
  <!-- cell bg lines -->
  <line x1="248" y1="246" x2="248" y2="304" stroke="rgba(74,186,112,0.1)" stroke-width="1"/>
  <line x1="452" y1="246" x2="452" y2="304" stroke="rgba(74,186,112,0.1)" stroke-width="1"/>
  <line x1="656" y1="246" x2="656" y2="304" stroke="rgba(74,186,112,0.1)" stroke-width="1"/>

  <!-- cred 01 -->
  <text x="52"  y="264" class="mono" font-size="8"  fill="#2a4a2a" letter-spacing="1">01</text>
  <text x="52"  y="280" class="mono" font-size="12" fill="#c8d8c0" font-weight="700">Commercial Pilot</text>
  <text x="52"  y="296" class="mono" font-size="9"  fill="#4a6a4a">Licensed CPL holder</text>
  <!-- cred 02 -->
  <text x="258" y="264" class="mono" font-size="8"  fill="#2a4a2a" letter-spacing="1">02</text>
  <text x="258" y="280" class="mono" font-size="12" fill="#c8d8c0" font-weight="700">MSc Cybersecurity</text>
  <text x="258" y="296" class="mono" font-size="9"  fill="#4a6a4a">Postgraduate degree</text>
  <!-- cred 03 -->
  <text x="462" y="264" class="mono" font-size="8"  fill="#2a4a2a" letter-spacing="1">03</text>
  <text x="462" y="280" class="mono" font-size="12" fill="#c8d8c0" font-weight="700">BSc Dev &amp; CS</text>
  <text x="462" y="296" class="mono" font-size="9"  fill="#4a6a4a">Full Stack + Comp. Sci.</text>
  <!-- cred 04 -->
  <text x="664" y="264" class="mono" font-size="8"  fill="#2a4a2a" letter-spacing="1">04</text>
  <text x="664" y="280" class="mono" font-size="12" fill="#c8d8c0" font-weight="700">Bug Bounty Hunter</text>
  <text x="664" y="296" class="mono" font-size="9"  fill="#4a6a4a">Responsible disclosure</text>

  <line x1="44" y1="308" x2="816" y2="308" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>

  <!-- ══ SECTION: STACK ══ -->
  <text x="44" y="330" class="mono" font-size="9" fill="#4aba70" letter-spacing="3">// PRIMARY STACK</text>
  <line x1="44" y1="335" x2="816" y2="335" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>

  <!-- stack pills row 1 -->
  <rect x="44"  y="342" width="88"  height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="52"  y="357" class="mono" font-size="10" fill="#7aaa7a">> Next.js</text>
  <rect x="140" y="342" width="102" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="148" y="357" class="mono" font-size="10" fill="#7aaa7a">> TypeScript</text>
  <rect x="250" y="342" width="90"  height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="258" y="357" class="mono" font-size="10" fill="#7aaa7a">> Flutter</text>
  <rect x="348" y="342" width="72"  height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="356" y="357" class="mono" font-size="10" fill="#7aaa7a">> Expo</text>
  <rect x="428" y="342" width="84"  height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="436" y="357" class="mono" font-size="10" fill="#7aaa7a">> Node.js</text>
  <rect x="520" y="342" width="80"  height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="528" y="357" class="mono" font-size="10" fill="#7aaa7a">> Python</text>
  <rect x="608" y="342" width="110" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="616" y="357" class="mono" font-size="10" fill="#7aaa7a">> PostgreSQL</text>
  <!-- row 2 -->
  <rect x="44"  y="370" width="118" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="52"  y="385" class="mono" font-size="10" fill="#7aaa7a">> Cybersecurity</text>
  <rect x="170" y="370" width="100" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="178" y="385" class="mono" font-size="10" fill="#7aaa7a">> OSINT Tools</text>
  <rect x="278" y="370" width="128" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="286" y="385" class="mono" font-size="10" fill="#7aaa7a">> SEO Automation</text>
  <rect x="414" y="370" width="104" height="22" rx="2" fill="rgba(74,186,112,0.07)" stroke="rgba(74,186,112,0.2)" stroke-width="0.5"/>
  <text x="422" y="385" class="mono" font-size="10" fill="#7aaa7a">> AI Pipelines</text>

  <line x1="44" y1="400" x2="816" y2="400" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>

  <!-- ══ SECTION: TOOL STATUS ══ -->
  <text x="44" y="422" class="mono" font-size="9" fill="#4aba70" letter-spacing="3">// TOOL STATUS</text>

  <!-- inner hud box -->
  <rect x="44" y="430" width="772" height="78" fill="rgba(74,186,112,0.03)" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>
  <polyline points="44,442 44,430 56,430" fill="none" stroke="#4aba70" stroke-width="1.5"/>
  <polyline points="804,430 816,430 816,442" fill="none" stroke="#4aba70" stroke-width="1.5"/>
  <polyline points="44,496 44,508 56,508" fill="none" stroke="#4aba70" stroke-width="1.5"/>
  <polyline points="804,508 816,508 816,496" fill="none" stroke="#4aba70" stroke-width="1.5"/>

  <text x="58" y="449" class="mono" font-size="9" fill="#2d5a2d" letter-spacing="1">[ PENDING ]</text>
  <text x="140" y="449" class="mono" font-size="9" fill="#7aaa7a">Website &amp; full tool suite — deployment imminent</text>

  <text x="58" y="466" class="mono" font-size="9" fill="#4aba70" letter-spacing="1">[ ACTIVE  ]</text>
  <text x="140" y="466" class="mono" font-size="9" fill="#7aaa7a">Back-end tooling for SEO, cybersecurity &amp; marketing depts.</text>

  <text x="58" y="483" class="mono" font-size="9" fill="#4aba70" letter-spacing="1">[ ACTIVE  ]</text>
  <text x="140" y="483" class="mono" font-size="9" fill="#7aaa7a">AI-assisted workflows, automation pipelines &amp; research</text>

  <text x="58" y="500" class="mono" font-size="9" fill="#4aba70" letter-spacing="1">[ HUNTING ]</text>
  <text x="140" y="500" class="mono" font-size="9" fill="#7aaa7a">Bug bounties — responsible disclosure, coordinated reporting</text>

  <!-- ══ ETHICS / DISCLAIMER ══ -->
  <line x1="44" y1="522" x2="816" y2="522" stroke="rgba(74,186,112,0.12)" stroke-width="1"/>
  <rect x="44" y="526" width="4" height="52" fill="#1a3a1a"/>

  <text x="58" y="541" class="mono" font-size="9" fill="#4a6a4a">[ LEGAL ]  All tools are for educational and lawful use only. Do not operate automation tools in ways that may constitute</text>
  <text x="58" y="555" class="mono" font-size="9" fill="#4a6a4a">a denial-of-service attack or violate a platform's ToS. Irresponsible rate config may result in IP bans or legal action.</text>
  <text x="58" y="569" class="mono" font-size="9" fill="#3d5a3d">[ SECURITY ]  Pen-testing tools are practice environments for students only — not for unauthorised real-world use.</text>

  <!-- ══ FOOTER ══ -->
  <line x1="44" y1="585" x2="816" y2="585" stroke="rgba(74,186,112,0.1)" stroke-width="1"/>
  <circle cx="56" cy="596" r="3" fill="#4aba70" class="cursor"/>
  <text x="64"  y="599" class="mono" font-size="9" fill="#2a4a2a" letter-spacing="1">ONLINE — DUBLIN, IRELAND</text>
  <text x="730" y="599" class="mono" font-size="9" fill="#2a4a2a" text-anchor="end" letter-spacing="1">github.com // 2026</text>
</svg>

</div>

<!-- typing SVG subtitle — works on GitHub -->
<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Space+Mono&size=14&pause=1200&color=4ABA70&center=true&vCenter=true&width=600&lines=Back-end+tools+for+real+problems.;CPL+%E2%9C%88+%7C+MSc+Cybersec+%7C+BSc+Dev+%26+CS;Cybersecurity+%2F+SEO+%2F+AI+Tooling.;Building+from+Dublin%2C+Ireland.)

</div>
