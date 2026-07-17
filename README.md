<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <defs>
    <!-- Background gradient -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>

    <!-- Animated border gradient -->
    <linearGradient id="borderGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00d9ff">
        <animate attributeName="stop-color" values="#00d9ff;#a855f7;#ec4899;#00d9ff" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#a855f7">
        <animate attributeName="stop-color" values="#a855f7;#ec4899;#00d9ff;#a855f7" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#ec4899">
        <animate attributeName="stop-color" values="#ec4899;#00d9ff;#a855f7;#ec4899" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- ASCII gradient -->
    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#00f5ff">
        <animate attributeName="stop-color" values="#00f5ff;#c471ed;#f64f59;#00f5ff" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#c471ed">
        <animate attributeName="stop-color" values="#c471ed;#f64f59;#00f5ff;#c471ed" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Name gradient -->
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#58a6ff"/>
      <stop offset="50%" stop-color="#a855f7"/>
      <stop offset="100%" stop-color="#ec4899"/>
    </linearGradient>

    <linearGradient id="pillGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#1f2937"/>
      <stop offset="100%" stop-color="#111827"/>
    </linearGradient>

    <filter id="glow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="3.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <filter id="softGlow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="1.6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <clipPath id="cardClip">
      <rect x="1" y="1" width="1178" height="608" rx="22"/>
    </clipPath>

    <clipPath id="titleClip">
      <path d="M2,20 A20,20 0 0 1 22,2 H1158 A20,20 0 0 1 1178,20 V56 H2 Z"/>
    </clipPath>

    <!-- Typing clip paths for role phrases -->
    <clipPath id="clipP1"><rect id="rP1" x="0" y="0" width="0" height="30"/></clipPath>
    <clipPath id="clipP2"><rect id="rP2" x="0" y="0" width="0" height="30"/></clipPath>
    <clipPath id="clipP3"><rect id="rP3" x="0" y="0" width="0" height="30"/></clipPath>
    <clipPath id="clipP4"><rect id="rP4" x="0" y="0" width="0" height="30"/></clipPath>
  </defs>

  <!-- Outer glow border -->
  <rect x="0" y="0" width="1180" height="610" rx="24" fill="url(#borderGrad)"/>
  <!-- Main card -->
  <rect x="3" y="3" width="1174" height="604" rx="21" fill="url(#bgGrad)"/>

  <g clip-path="url(#cardClip)">

    <!-- ================= LEFT PANEL ================= -->
    <rect x="0" y="0" width="448" height="610" fill="#0a0e14"/>

    <!-- vertical divider -->
    <rect x="447" y="0" width="2" height="610" fill="url(#borderGrad)" opacity="0.5"/>

    <!-- floating ascii group -->
    <g id="asciiFloat" font-family="'Courier New', Consolas, monospace" font-size="15" fill="url(#asciiGrad)" filter="url(#glow)">
      <animateTransform attributeName="transform" type="translate" values="0,0; 0,-8; 0,0" dur="4.5s" repeatCount="indefinite"/>

      <text x="60" y="90" opacity="0">┌──────────────────┐<animate attributeName="opacity" to="1" begin="0.3s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="118" opacity="0">│   ▄▄▄▄▄▄▄▄▄▄▄▄   │<animate attributeName="opacity" to="1" begin="0.55s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="146" opacity="0">│  █  ●      ●  █  │<animate attributeName="opacity" to="1" begin="0.8s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="174" opacity="0">│  █    ▄▄▄▄    █  │<animate attributeName="opacity" to="1" begin="1.05s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="202" opacity="0">│  █   ▀▀▀▀▀▀   █  │<animate attributeName="opacity" to="1" begin="1.3s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="230" opacity="0">│   ▀▀▀▀▀▀▀▀▀▀▀▀   │<animate attributeName="opacity" to="1" begin="1.55s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="258" opacity="0">│                  │<animate attributeName="opacity" to="1" begin="1.8s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="286" opacity="0">│   SYSTEM: ONLINE │<animate attributeName="opacity" to="1" begin="2.05s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="314" opacity="0">│   MODE: BUILD    │<animate attributeName="opacity" to="1" begin="2.3s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="342" opacity="0">│  [■■■■■■■■■□□]   │<animate attributeName="opacity" to="1" begin="2.55s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="370" opacity="0">│    82% SHIPPED   │<animate attributeName="opacity" to="1" begin="2.8s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="398" opacity="0">└──────────────────┘<animate attributeName="opacity" to="1" begin="3.05s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="426" opacity="0">        ║  ║  ║<animate attributeName="opacity" to="1" begin="3.3s" dur="0.01s" fill="freeze"/></text>
      <text x="60" y="454" opacity="0" font-weight="bold">  &lt;yashwanth412/&gt;<animate attributeName="opacity" to="1" begin="3.55s" dur="0.01s" fill="freeze"/></text>

      <!-- blinking cursor after last line -->
      <rect x="248" y="440" width="10" height="18" fill="#00f5ff" opacity="0">
        <animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.85;0.92;1" begin="3.7s" dur="1s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- scanline sweep -->
    <rect x="45" y="70" width="360" height="3" fill="#00f5ff" opacity="0.12">
      <animate attributeName="y" values="70;480;70" dur="3.2s" begin="1s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.18;0" dur="3.2s" begin="1s" repeatCount="indefinite"/>
    </rect>

    <!-- subtle scanline grid overlay -->
    <g opacity="0.05">
      <rect x="0" y="0" width="448" height="2" fill="#ffffff"/>
      <rect x="0" y="8" width="448" height="1" fill="#ffffff"/>
      <rect x="0" y="16" width="448" height="1" fill="#ffffff"/>
    </g>

    <text x="60" y="500" font-family="'Courier New', monospace" font-size="12" fill="#3fb950" opacity="0">
      root@dev-terminal: connection secure
      <animate attributeName="opacity" to="0.75" begin="4s" dur="0.01s" fill="freeze"/>
    </text>

    <!-- ================= RIGHT PANEL ================= -->
    <!-- Terminal window -->
    <rect x="480" y="40" width="660" height="530" rx="14" fill="#161b22" stroke="#30363d" stroke-width="1.5"/>
    <path d="M480,54 A14,14 0 0 1 494,40 H1126 A14,14 0 0 1 1140,54 V76 H480 Z" fill="#1c2128"/>
    <circle cx="507" cy="58" r="6" fill="#ff5f56"/>
    <circle cx="527" cy="58" r="6" fill="#ffbd2e"/>
    <circle cx="547" cy="58" r="6" fill="#27c93f"/>
    <text x="575" y="63" font-family="'Courier New', monospace" font-size="13" fill="#8b949e">yashwanth@dev:~</text>

    <!-- Greeting -->
    <text x="520" y="122" font-family="'Segoe UI', Ubuntu, sans-serif" font-size="26" fill="#c9d1d9" opacity="0">
      Hi
      <animate attributeName="opacity" to="1" begin="0.3s" dur="0.01s" fill="freeze"/>
    </text>
    <text x="558" y="122" font-size="26" opacity="0">
      👋
      <animate attributeName="opacity" to="1" begin="0.3s" dur="0.01s" fill="freeze"/>
    </text>

    <text x="520" y="168" font-family="'Segoe UI', Ubuntu, sans-serif" font-size="34" font-weight="700" fill="url(#nameGrad)" opacity="0" filter="url(#softGlow)">
      I'm Yashwanth Pasupuleti
      <animate attributeName="opacity" to="1" begin="0.7s" dur="0.01s" fill="freeze"/>
    </text>

    <!-- Typing role line -->
    <text x="520" y="205" font-family="'Courier New', monospace" font-size="20" fill="#58a6ff">&gt;</text>

    <g font-family="'Courier New', monospace" font-size="20" fill="#e6edf3" font-weight="600">
      <g clip-path="url(#clipP1)">
        <text x="542" y="205">Full Stack Developer</text>
      </g>
      <g clip-path="url(#clipP2)">
        <text x="542" y="205">Indie SaaS Builder</text>
      </g>
      <g clip-path="url(#clipP3)">
        <text x="542" y="205">Data Analyst</text>
      </g>
      <g clip-path="url(#clipP4)">
        <text x="542" y="205">AI-Assisted Dev</text>
      </g>
    </g>

    <!-- clip rect width animations driving the typewriter reveal, 12s full cycle -->
    <rect x="0" y="0" width="0" height="30" opacity="0">
      <animate xlink:href="#rP1" attributeName="width"
        keyTimes="0;0.0833;0.1833;0.2333;1"
        values="0;255;255;0;0" dur="12s" begin="1s" repeatCount="indefinite"/>
    </rect>
    <rect x="0" y="0" width="0" height="30" opacity="0">
      <animate xlink:href="#rP2" attributeName="width"
        keyTimes="0;0.25;0.3333;0.4333;0.4833;1"
        values="0;0;225;225;0;0" dur="12s" begin="1s" repeatCount="indefinite"/>
    </rect>
    <rect x="0" y="0" width="0" height="30" opacity="0">
      <animate xlink:href="#rP3" attributeName="width"
        keyTimes="0;0.5;0.5833;0.6833;0.7333;1"
        values="0;0;150;150;0;0" dur="12s" begin="1s" repeatCount="indefinite"/>
    </rect>
    <rect x="0" y="0" width="0" height="30" opacity="0">
      <animate xlink:href="#rP4" attributeName="width"
        keyTimes="0;0.75;0.8333;0.9333;0.9833;1"
        values="0;0;190;190;0;0" dur="12s" begin="1s" repeatCount="indefinite"/>
    </rect>

    <!-- blinking cursor for role line -->
    <rect x="732" y="188" width="10" height="20" fill="#58a6ff">
      <animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/>
    </rect>

    <!-- Info rows -->
    <g font-family="'Courier New', monospace" font-size="16" fill="#8b949e">
      <text x="520" y="255" opacity="0">
        <tspan fill="#58a6ff">▸ Location:</tspan> Nellore, Andhra Pradesh, India
        <animate attributeName="opacity" to="1" begin="1.4s" dur="0.01s" fill="freeze"/>
      </text>
      <text x="520" y="283" opacity="0">
        <tspan fill="#58a6ff">▸ Education:</tspan> B.Tech, ECE — Narayana Engineering College
        <animate attributeName="opacity" to="1" begin="1.65s" dur="0.01s" fill="freeze"/>
      </text>
      <text x="520" y="311" opacity="0">
        <tspan fill="#58a6ff">▸ Current Focus:</tspan> Building BhaiCA — SaaS for CAs
        <animate attributeName="opacity" to="1" begin="1.9s" dur="0.01s" fill="freeze"/>
      </text>
      <text x="520" y="339" opacity="0">
        <tspan fill="#58a6ff">▸ Portfolio:</tspan> github.com/yashwanth412
        <animate attributeName="opacity" to="1" begin="2.15s" dur="0.01s" fill="freeze"/>
      </text>
      <text x="520" y="367" opacity="0">
        <tspan fill="#58a6ff">▸ Email:</tspan> pasupuleti.yashwanth0412@gmail.com
        <animate attributeName="opacity" to="1" begin="2.4s" dur="0.01s" fill="freeze"/>
      </text>
    </g>

    <!-- Tech stack label -->
    <text x="520" y="415" font-family="'Segoe UI', Ubuntu, sans-serif" font-size="16" font-weight="700" fill="#c9d1d9" opacity="0">
      Tech Stack
      <animate attributeName="opacity" to="1" begin="2.65s" dur="0.01s" fill="freeze"/>
    </text>

    <!-- Skill pills -->
    <g font-family="'Courier New', monospace" font-size="14" font-weight="600">
      <!-- Row 1 -->
      <g opacity="0">
        <animate attributeName="opacity" to="1" begin="2.8s" dur="0.01s" fill="freeze"/>
        <rect x="520" y="435" width="75" height="34" rx="17" fill="url(#pillGrad)" stroke="#00d9ff" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="3s" repeatCount="indefinite"/>
        </rect>
        <text x="557" y="457" fill="#79c0ff" text-anchor="middle">React</text>

        <rect x="609" y="435" width="85" height="34" rx="17" fill="url(#pillGrad)" stroke="#a855f7" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="3.2s" repeatCount="indefinite"/>
        </rect>
        <text x="651" y="457" fill="#d2a8ff" text-anchor="middle">Django</text>

        <rect x="708" y="435" width="85" height="34" rx="17" fill="url(#pillGrad)" stroke="#ec4899" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="3.4s" repeatCount="indefinite"/>
        </rect>
        <text x="750" y="457" fill="#f2a5c9" text-anchor="middle">Python</text>

        <rect x="807" y="435" width="100" height="34" rx="17" fill="url(#pillGrad)" stroke="#00d9ff" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="3.6s" repeatCount="indefinite"/>
        </rect>
        <text x="857" y="457" fill="#79c0ff" text-anchor="middle">Supabase</text>
      </g>

      <!-- Row 2 -->
      <g opacity="0">
        <animate attributeName="opacity" to="1" begin="3s" dur="0.01s" fill="freeze"/>
        <rect x="520" y="480" width="75" height="34" rx="17" fill="url(#pillGrad)" stroke="#a855f7" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="3.8s" repeatCount="indefinite"/>
        </rect>
        <text x="557" y="502" fill="#d2a8ff" text-anchor="middle">Azure</text>

        <rect x="609" y="480" width="100" height="34" rx="17" fill="url(#pillGrad)" stroke="#ec4899" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="4s" repeatCount="indefinite"/>
        </rect>
        <text x="659" y="502" fill="#f2a5c9" text-anchor="middle">Power BI</text>

        <rect x="723" y="480" width="100" height="34" rx="17" fill="url(#pillGrad)" stroke="#00d9ff" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="4.2s" repeatCount="indefinite"/>
        </rect>
        <text x="773" y="502" fill="#79c0ff" text-anchor="middle">Tailwind</text>

        <rect x="837" y="480" width="60" height="34" rx="17" fill="url(#pillGrad)" stroke="#a855f7" stroke-width="1.2" filter="url(#softGlow)">
          <animate attributeName="opacity" values="0.85;1;0.85" dur="2.4s" begin="4.4s" repeatCount="indefinite"/>
        </rect>
        <text x="867" y="502" fill="#d2a8ff" text-anchor="middle">SQL</text>
      </g>
    </g>

    <!-- bottom status bar -->
    <text x="520" y="545" font-family="'Courier New', monospace" font-size="12" fill="#3fb950" opacity="0">
      ● Available for freelance work
      <animate attributeName="opacity" to="0.85" begin="4.6s" dur="0.01s" fill="freeze"/>
    </text>
  </g>
</svg>
