![terminal](https://github.com/user-attachments/assets/a7588e5e-b933-4c4f-9ef8-07bc1c4dff33)
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 420" width="700" height="420">
  <defs>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&amp;display=swap');
      .bg { fill: #080810; }
      .tb { fill: #0d0d1a; }
      .dr { fill: #ff5f57; }
      .dy { fill: #febc2e; }
      .dg { fill: #28c840; }
      .tname { fill: #3d2060; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 11px; }
      .ps { fill: #9b30ff; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .pa { fill: #5c3d99; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .pp { fill: #4a9eff; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .cmd { fill: #d4c5f0; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .op { fill: #9b30ff; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .ob { fill: #4a9eff; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .og { fill: #39d353; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .or { fill: #ff4a6e; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .oy { fill: #e5c07b; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .od { fill: #3d2060; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .ow { fill: #8b7aaa; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .oc { fill: #56b6c2; font-family: 'JetBrains Mono', 'Courier New', monospace; font-size: 12.5px; }
      .cursor { fill: #9b30ff; }
    </style>

    <!-- Scanline pattern -->
    <pattern id="scan" x="0" y="0" width="700" height="4" patternUnits="userSpaceOnUse">
      <rect width="700" height="2" fill="transparent"/>
      <rect y="2" width="700" height="2" fill="rgba(0,0,0,0.07)"/>
    </pattern>
  </defs>

  <!-- Background -->
  <rect width="700" height="420" rx="10" class="bg"/>
  <!-- Titlebar -->
  <rect width="700" height="34" rx="10" class="tb"/>
  <rect y="24" width="700" height="10" class="tb"/>
  <rect y="24" width="700" height="1" fill="#1a0a2e"/>
  <!-- Dots -->
  <circle cx="20" cy="17" r="5.5" class="dr"/>
  <circle cx="38" cy="17" r="5.5" class="dy"/>
  <circle cx="56" cy="17" r="5.5" class="dg"/>
  <!-- Title -->
  <text x="350" y="21" text-anchor="middle" class="tname">youcef@night-city — bash</text>
  <!-- Scanlines overlay -->
  <rect width="700" height="420" rx="10" fill="url(#scan)" opacity="0.5"/>

  <!-- LINE 1: prompt + whoami (appears at 0.3s) -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="0.3s" fill="freeze"/>
    <text x="26" y="68"><tspan class="ps">youcef</tspan><tspan class="pa">@</tspan><tspan class="pp">night-city</tspan><tspan class="ps">:~ $</tspan><tspan class="cmd"> whoami</tspan></text>
  </g>

  <!-- LINE 2: youcef cherbal (appears at 0.9s) -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="0.9s" fill="freeze"/>
    <text x="26" y="88" class="op">youcef cherbal</text>
  </g>

  <!-- LINE 3: prompt + cat about.txt (appears at 1.3s) -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="1.3s" fill="freeze"/>
    <text x="26" y="112"><tspan class="ps">youcef</tspan><tspan class="pa">@</tspan><tspan class="pp">night-city</tspan><tspan class="ps">:~ $</tspan><tspan class="cmd"> cat about.txt</tspan></text>
  </g>

  <!-- LINE 4: age info -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="1.8s" fill="freeze"/>
    <text x="26" y="132" class="ow">16 y/o · CS Student · Spain</text>
  </g>

  <!-- LINE 5: roles -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.1s" fill="freeze"/>
    <text x="26" y="152" class="ow">Offensive security learner · Web dev · Video editor</text>
  </g>

  <!-- LINE 6: prompt + ls skills -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="2.6s" fill="freeze"/>
    <text x="26" y="176"><tspan class="ps">youcef</tspan><tspan class="pa">@</tspan><tspan class="pp">night-city</tspan><tspan class="ps">:~ $</tspan><tspan class="cmd"> ls ./skills/</tspan></text>
  </g>

  <!-- LINE 7: skills row 1 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="3.1s" fill="freeze"/>
    <text x="26" y="196" class="ob">JavaScript/  Python/  HTML+CSS/  Node.js/  Bash/</text>
  </g>

  <!-- LINE 8: skills row 2 security -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="3.4s" fill="freeze"/>
    <text x="26" y="216" class="ob">Nmap/  BurpSuite/  SQLmap/  Recon/  OSINT/  Kali/</text>
  </g>

  <!-- LINE 9: prompt + nmap -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="3.9s" fill="freeze"/>
    <text x="26" y="240"><tspan class="ps">youcef</tspan><tspan class="pa">@</tspan><tspan class="pp">night-city</tspan><tspan class="ps">:~ $</tspan><tspan class="cmd"> nmap -sV --open target.lab</tspan></text>
  </g>

  <!-- LINE 10: nmap header -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="4.5s" fill="freeze"/>
    <text x="26" y="260" class="od">Starting Nmap 7.94 ( https://nmap.org )</text>
  </g>

  <!-- LINE 11: port header -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="4.8s" fill="freeze"/>
    <text x="26" y="280" class="ow">PORT      STATE  SERVICE    VERSION</text>
  </g>

  <!-- LINE 12: port 22 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="5.1s" fill="freeze"/>
    <text x="26" y="300" class="oy">22/tcp    open   ssh        OpenSSH 8.9</text>
  </g>

  <!-- LINE 13: port 80 -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="5.3s" fill="freeze"/>
    <text x="26" y="320" class="oy">80/tcp    open   http       nginx 1.24.0</text>
  </g>

  <!-- LINE 14: vuln port -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="5.6s" fill="freeze"/>
    <text x="26" y="340" class="or">8080/tcp  open   http       [!] VULN: Unrestricted upload</text>
  </g>

  <!-- LINE 15: exploit -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="6.1s" fill="freeze"/>
    <text x="26" y="364"><tspan class="ps">youcef</tspan><tspan class="pa">@</tspan><tspan class="pp">night-city</tspan><tspan class="ps">:~ $</tspan><tspan class="cmd"> python3 exploit.py --lhost 10.10.14.1 --lport 4444</tspan></text>
  </g>

  <!-- LINE 16: shell obtained -->
  <g opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="6.8s" fill="freeze"/>
    <text x="26" y="384" class="og">[ + ] Shell spawned — UID=0(root) — authorized engagement</text>
  </g>

  <!-- Blinking cursor — visible before lines appear then stays at end -->
  <rect x="26" y="396" width="7" height="13" class="cursor">
    <animate attributeName="opacity" values="1;0;1" dur="1.1s" begin="7.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0" dur="0.1s" begin="0s" fill="freeze"/>
    <animate attributeName="opacity" values="0;1" dur="0.1s" begin="7.2s" fill="freeze"/>
  </rect>
</svg>

<div align="center">

![terminal](./terminal.svg)

</div>

### 🌐 Portfolio
[lleagyy.github.io/youcef](https://lleagyy.github.io/youcef)
