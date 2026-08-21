<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1180 610" width="100%" height="100%">
  <defs>
    <style>
      .bg { fill: #0A101F; rx: 12px; }
      .border { stroke: #1E293B; stroke-width: 1.5; fill: none; }
      .title { font-family: ui-monospace, monospace; font-size: 13px; fill: #64748B; }
      .text-key { font-family: ui-monospace, monospace; font-size: 14px; fill: #22D3EE; font-weight: 600; }
      .text-val { font-family: ui-monospace, monospace; font-size: 14px; fill: #F8FAFC; }
      .leader { font-family: ui-monospace, monospace; font-size: 14px; fill: #334155; }
      .pill { fill: #1E1B4B; rx: 6px; }
      .pill-text { font-family: ui-monospace, monospace; font-size: 13px; fill: #A78BFA; font-weight: bold; }
      .live-dot { fill: #EF4444; }
      .live-text { font-family: ui-monospace, monospace; font-size: 12px; fill: #EF4444; font-weight: bold; }
    </style>
  </defs>

  <!-- Background Window -->
  <rect width="1180" height="610" class="bg" />
  <rect width="1180" height="610" class="border" rx="12" />

  <!-- Top Terminal Bar -->
  <circle cx="30" cy="30" r="6" fill="#EF4444" />
  <circle cx="50" cy="30" r="6" fill="#F59E0B" />
  <circle cx="70" cy="30" r="6" fill="#10B981" />
  <text x="100" y="35" class="title">profile.sh-live</text>

  <!-- Status Badges Top Right -->
  <circle cx="1020" cy="30" r="4" class="live-dot">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite" />
  </circle>
  <text x="1032" y="34" class="live-text">LIVE</text>
  <rect x="1075" y="18" width="80" height="24" class="pill" />
  <text x="1087" y="34" class="pill-text">@loharbijoy</text>

  <!-- Left Frame: Dither Placeholder / Visual Map -->
  <rect x="35" y="70" width="410" height="505" fill="#0D1527" rx="8" stroke="#1E293B" />
  <text x="50" y="95" class="title" fill="#22D3EE">VISUAL.MAP</text>
  
  <!-- Cyberpunk Matrix Glyph Animation -->
  <g fill="#A78BFA" opacity="0.85">
    <text x="70" y="240" font-family="monospace" font-size="12">01000010 01001001 01001010 01001111 01011001</text>
    <text x="70" y="270" font-family="monospace" font-size="12">01001100 01001111 01001000 01000001 01010010</text>
    <text x="70" y="310" font-family="monospace" font-size="15" fill="#22D3EE">&lt;/&gt; FULL-STACK &amp; AI ENGINE</text>
    <circle cx="240" cy="400" r="40" fill="none" stroke="#10B981" stroke-width="2" stroke-dasharray="6,6">
      <animateTransform attributeName="transform" type="rotate" from="0 240 400" to="360 240 400" dur="10s" repeatCount="indefinite"/>
    </circle>
    <circle cx="240" cy="400" r="20" fill="none" stroke="#A78BFA" stroke-width="1.5" />
    <text x="227" y="405" font-family="monospace" font-size="14" fill="#22D3EE">AI</text>
  </g>

  <!-- Right Frame: System Info -->
  <rect x="465" y="70" width="680" height="505" fill="#0D1527" rx="8" stroke="#1E293B" />
  <text x="485" y="95" class="title" fill="#22D3EE">SYSTEM.INFO</text>

  <!-- Info Rows -->
  <g transform="translate(485, 130)">
    <!-- Row 1 -->
    <text y="0" class="text-key">Subject</text>
    <text x="140" y="0" class="leader">....................................</text>
    <text x="430" y="0" class="text-val">Bijoy Lohar</text>

    <!-- Row 2 -->
    <text y="28" class="text-key">Role</text>
    <text x="140" y="28" class="leader">....................................</text>
    <text x="350" y="28" class="text-val">Full-Stack Dev &amp; AI Eng</text>

    <!-- Row 3 -->
    <text y="56" class="text-key">Origin</text>
    <text x="140" y="56" class="leader">....................................</text>
    <text x="410" y="56" class="text-val">Bishnupur, WB, IN</text>

    <!-- Row 4 -->
    <text y="84" class="text-key">Education</text>
    <text x="140" y="84" class="leader">....................................</text>
    <text x="375" y="84" class="text-val">Pursuing B.Tech Degree</text>

    <!-- Row 5 -->
    <text y="112" class="text-key">Status</text>
    <text x="140" y="112" class="leader">....................................</text>
    <text x="370" y="112" class="text-val" fill="#10B981">Shipping Apps &amp; Models</text>

    <!-- Row 6 -->
    <text y="140" class="text-key">ToolChain</text>
    <text x="140" y="140" class="leader">....................................</text>
    <text x="420" y="140" class="text-val">VS Code, Git, GitHub</text>

    <!-- Row 7 -->
    <text y="168" class="text-key">Core.Lang</text>
    <text x="140" y="168" class="leader">....................................</text>
    <text x="360" y="168" class="text-val">JS, TypeScript, Python</text>

    <!-- Row 8 -->
    <text y="196" class="text-key">Core.Frontend</text>
    <text x="140" y="196" class="leader">....................................</text>
    <text x="390" y="196" class="text-val">HTML5, CSS3, React</text>

    <!-- Row 9 -->
    <text y="224" class="text-key">Core.Backend</text>
    <text x="140" y="224" class="leader">....................................</text>
    <text x="375" y="224" class="text-val">Node.js, Express, REST</text>

    <!-- Row 10 -->
    <text y="252" class="text-key">Core.Database</text>
    <text x="140" y="252" class="leader">....................................</text>
    <text x="455" y="252" class="text-val">MongoDB</text>

    <!-- Row 11 -->
    <text y="280" class="text-key">Core.Infra</text>
    <text x="140" y="280" class="leader">....................................</text>
    <text x="405" y="280" class="text-val">Vercel, Render, Cloud</text>

    <!-- Row 12 -->
    <text y="308" class="text-key">Grid.Facebook</text>
    <text x="140" y="308" class="leader">....................................</text>
    <text x="430" y="308" class="text-val" fill="#1877F2">Connected</text>

    <!-- Row 13 -->
    <text y="336" class="text-key">Grid.Insta</text>
    <text x="140" y="336" class="leader">....................................</text>
    <text x="430" y="336" class="text-val" fill="#E4405F">Connected</text>
  </g>
</svg>
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 10
    steps:
      - name: Generate snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg?palette=github-light&color_snake=0891B2&color_dots=#ebedf0,#a5b4fc,#818cf8,#6366f1,#089182
            dist/github-snake-dark.svg?palette=github-dark&color_snake=10B981&color_dots=#2d3343,#4b5563,#7C3AED,#A78BFA,#22D3EE
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
          commit_message: "Update snake animation [skip ci]"
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<!-- Terminal Banner with Automatic Theme Switching -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/main/dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/main/light.svg">
    <img alt="Bijoy Lohar Terminal Profile" src="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/main/dark.svg" width="100%">
  </picture>
</div>

<br/>

<!-- Dynamic Activity Streak Stats -->
<div align="center">
  <img width="100%" src="https://streak-stats.demolab.com/?user=loharbijoy2005-a11y&amp;hide_border=true&amp;background=0A101F&amp;stroke=22D3EE&amp;ring=A78BFA&amp;fire=10B981&amp;currStreakLabel=22D3EE&amp;sideLabels=94A3B8&amp;currStreakNum=F8FAFC&amp;sideNums=F8FAFC&amp;dates=64748B&amp;titleColor=22D3EE" alt="Streak Stats" />
</div>

<br/>

<!-- GitHub Stats and Languages (Using Stable Public Endpoints) -->
<div align="center">
  <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api?username=loharbijoy2005-a11y&amp;show_icons=true&amp;count_private=true&amp;include_all_commits=true&amp;hide_rank=true&amp;hide_border=true&amp;title_color=22D3EE&amp;icon_color=A78BFA&amp;text_color=94A3B8&amp;bg_color=0A101F" alt="GitHub Stats" />
  <img width="49%" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=loharbijoy2005-a11y&amp;layout=compact&amp;langs_count=8&amp;hide_border=true&amp;title_color=22D3EE&amp;text_color=94A3B8&amp;bg_color=0A101F" alt="Top Languages" />
</div>

<br/>

<!-- Contribution Snake Animation -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/output/github-snake.svg" />
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/loharbijoy2005-a11y/loharbijoy2005-a11y/output/github-snake.svg" width="100%" />
  </picture>
</div>

<br/>

<!-- Social Badges -->
<div align="center">
  <a href="https://www.facebook.com/share/1DTZjnVBM3/" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-0A101F?style=for-the-badge&amp;logo=facebook&amp;logoColor=1877F2&amp;labelColor=0A101F" alt="Facebook" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.instagram.com/arrowgaming2005" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-0A101F?style=for-the-badge&amp;logo=instagram&amp;logoColor=E4405F&amp;labelColor=0A101F" alt="Instagram" />
  </a>
</div>
