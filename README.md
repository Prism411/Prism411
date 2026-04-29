<!--
  ╭─────────────────────────────────────────────────────────────╮
  │  jáder louis · github profile · readme v3                   │
  │  rendered in pure markdown + html                           │
  │  cats included for moral support                            │
  ╰─────────────────────────────────────────────────────────────╯
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0e27,40:1a3a5c,100:d4a574&height=240&section=header&text=jáder%20louis&fontSize=82&fontColor=f5e6d3&fontAlignY=38&desc=butantã%20·%20são%20paulo%20·%20SP&descSize=15&descAlignY=62&descAlign=50&fontFamily=JetBrains%20Mono&animation=fadeIn"/>

<a href="https://github.com/Prism411">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3400&pause=900&color=D4A574&center=true&vCenter=true&width=760&lines=graphs+%7C+NLP+%7C+CNNs+%7C+transformers+%7C+embeddings;building+systems+that+see%2C+listen+and+understand;MSc+AI+%40+ICMC-USP+%7C+geo-dev+%40+SEDAM-COGEO;ferrari+tifosi+%7C+factorio+%7C+racing+sims+%7C+F1+sundays" alt="typing"/>
</a>

</div>

<table align="center" border="0">
  <tr>
    <td align="center"><a href="https://github.com/prism411?tab=followers"><img src="https://img.shields.io/github/followers/prism411?style=flat-square&color=d4a574&labelColor=0a0e27&label=FOLLOWERS"/></a></td>
    <td align="center"><a href="https://github.com/prism411?tab=repositories"><img src="https://img.shields.io/github/stars/prism411?style=flat-square&color=d4a574&labelColor=0a0e27&label=STARS"/></a></td>
    <td align="center"><img src="https://komarev.com/ghpvc/?username=prism411&color=d4a574&style=flat-square&label=VISITS&labelColor=0a0e27"/></td>
    <td align="center"><img src="https://img.shields.io/badge/based_in-butantã_·_SP-d4a574?style=flat-square&labelColor=0a0e27"/></td>
    <td align="center"><img src="https://img.shields.io/badge/last_update-2026--04-d4a574?style=flat-square&labelColor=0a0e27"/></td>
  </tr>
</table>

<br/>

<!-- ───────────────────────────  HERO  ─────────────────────────── -->

<table border="0" align="center">
<tr>
<td width="58%" valign="top">

<h2>▍ <code>cat /home/jader/whoami.txt</code></h2>

```yaml
name:        jáder louis de souza gonçalves
role:        geospatial developer @ SEDAM / COGEO (remote)
study:       MSc AI @ ICMC-USP · multimodal artificial intelligence
research:    graphs + NLP + feature extraction
             + CNNs + transformers + embeddings
location:    butantã, são paulo · SP
languages:   pt-br (native) · en (fluent)
favorite:    well-named variables, leaflet-on-postgis,
             ferrari sundays, factorio late nights
```

<sub>this readme is part research log, part portfolio.</sub>

</td>
<td width="42%" valign="top" align="center">

<img src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="100%" alt="cat coding"/>

<sub><code>fig 1.</code> &nbsp; <em>my pair-programmer reviewing a PR.<br/>compensation: tuna, head scratches.</em></sub>

</td>
</tr>
</table>

<!-- ─────────────────────  ACTIVE RESEARCH  ───────────────────── -->

<h2>▍ active research <sup><code>2026·Q2</code></sup></h2>

<blockquote>
<p><sub>all dates absolute · venues confirmed · drafts at various depths of caffeine.</sub></p>
</blockquote>

<table>
<tr>
<td width="50%" valign="top">

<h3>🕸 <code>jl-summ-graph</code> &nbsp;<sub>· private</sub></h3>

<b>Graph-based multi-video news summarization (PT-BR).</b><br/>
Stratified kNN + temporal edges + Leiden-CPM communities → top-1-per-community selection with entity-density boosting. Beats <code>HSMVideoSumm</code> baseline by <kbd>+0.21 F1</kbd> at <kbd>~450× faster</kbd> runtime on a 17-topic news corpus.

<sub><code>python</code> · <code>networkx</code> · <code>e5-large</code> · <code>leiden</code> · <code>submodlib</code></sub><br/>
<sub>🎯 target · <b>WebMedia 2026</b> &nbsp;·&nbsp; status · experimental phase, no draft yet</sub>

</td>
<td width="50%" valign="top">

<h3>🎬 <a href="https://github.com/Prism411/sumarizador"><code>sumarizador</code> · SummWeb</a> &nbsp;<sub>· private</sub></h3>

<b>Programmable web platform for video summarization.</b><br/>
Next.js 15 + FastAPI + Docker. Visual flow builder, monitored folders, REST API for automation, decision logs. Catppuccin Mocha design system. Wraps the HSMVideoSumm engine.

<sub><code>next.js</code> · <code>fastapi</code> · <code>docker</code> · <code>react-flow</code></sub><br/>
<sub>🎯 target · <b>WebMedia 2026 · tool track</b> &nbsp;·&nbsp; status · in development</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>📊 <code>quality-benchmark</code> · Evaluality &nbsp;<sub>· private</sub></h3>

<b>Benchmark of 11 quality-scoring methods for multi-doc video summarization.</b><br/>
Sanity check + agreement analysis. SIFT shows 0% agreement; DINOv2 promising as proxy; BRISQUE/NIQE without ceiling effect.

<sub><code>pytorch</code> · <code>dinov2</code> · <code>brisque</code> · <code>niqe</code></sub><br/>
<sub>🎯 target · <b>WebMedia 2026 · full track</b> &nbsp;·&nbsp; status · 20-page draft</sub>

</td>
<td width="50%" valign="top">

<h3>🎮 <code>komplexity</code> &nbsp;<sub>· two papers, one engine</sub></h3>

<b>Code-complexity gamification platform.</b><br/>
Twin submissions: <b>SBGames 2026</b> (game-design lens, PT-BR) + <b>SBES-Edu 2026</b> (software-engineering education lens, EN, ACM format).

<sub><code>unity</code> · <code>c#</code> · <code>python</code> · <code>cs-metrics</code></sub><br/>
<sub>✅ submitted · <b>SBGames 2026</b> (27/abr) &nbsp;·&nbsp; ⏳ deadline · <b>SBES-Edu 2026</b> (11/mai)</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🗄 <code>CGKB</code> &nbsp;<sub>· short paper</sub></h3>

<b>Code Graph Knowledge Base — converts Python code to control flow and data dependency graphs for LLM-assisted code analysis.</b><br/>
Component of Conapse-Net. Short paper submitted to <b>SBBD 2026</b>.

<sub><code>python</code> · <code>knowledge graphs</code> · <code>postgresql</code></sub><br/>
<sub>⏳ deadline · <b>SBBD 2026</b> (30/abr)</sub>

</td>
<td width="50%" valign="top">

<h3>🧠 <code>Conapse-Net</code> &nbsp;<sub>· TCC · private</sub></h3>

<b>Neurosymbolic system for LLM optimization via code graphs.</b><br/>
Composed of <b>CGKB</b> (Code Graph Knowledge Base) and <b>RAC</b> (Rational Analysis Component — 26 specialized graph processors). Evaluated on DyPyBench (50 projects, 681k LOC): <kbd>84.7% token reduction</kbd>, <kbd>88.76% detection rate</kbd>, RAC 12B matches Llama 70B with 5.8× fewer params and 98% lower cost.

<sub><code>python</code> · <code>graphs</code> · <code>neurosymbolic AI</code> · <code>LLMs</code></sub><br/>
<sub>📄 submitted · <b>SBC</b> (TCC)</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🐟 <code>reconhecimento_peixes</code> &nbsp;<sub>· applied, no paper</sub></h3>

<b>ASR + NER pipeline for fishing-trip videos.</b><br/>
faster-whisper large-v3-turbo → GLiNER ONNX → Qwen2.5-7B extractor → Llama-3.1-8B verifier. Open-vocabulary capture for species, basins, baits.

<sub><code>whisper</code> · <code>gliner</code> · <code>ollama</code> · <code>qwen</code> · <code>llama</code></sub><br/>
<sub>📄 status · production pipeline, partner-facing</sub>

</td>
<td width="50%" valign="top">

<h3>🎮 <code>PRISMa</code> &nbsp;<sub>· multi-agent · private</sub></h3>

<b>Modular cognitively-inspired architecture with persistent memory for autonomous agents in open-world environments.</b><br/>
Evaluated in Minecraft. Persistent memory + modular cognition + multi-agent coordination.

<sub><code>python</code> · <code>multi-agent systems</code> · <code>minecraft</code> · <code>persistent memory</code></sub><br/>
<sub>🎯 target · <b>JAAMAS</b> (Springer)</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🛰 <code>PROTEGE</code> &nbsp;<sub>· SEDAM/COGEO · government</sub></h3>

<b>Geospatial monitoring stack for the state of Rondônia.</b><br/>
Maintenance + new features across <code>protege</code>, <code>protege-api</code>, <code>protege-datahub</code>, <code>protege-notificacoes</code>. Fire-spot dashboards, 3D route visualization, anomaly detection.

<sub><code>react</code> · <code>postgis</code> · <code>openlayers</code> · <code>airflow</code></sub><br/>
<sub>📄 status · in production · v0.7.4 prod / v0.7.5 dev</sub>

</td>
<td width="50%" valign="top"></td>
</tr>
</table>

<!-- ───────────────────────  PIXEL CAT BAR  ─────────────────────── -->

<div align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="snake eating contributions"/>
</div>

<!-- ─────────────────────────  PUBLIC  ──────────────────────────── -->

<h2>▍ public &amp; recent</h2>

<table>
<tr>
<th align="left"></th>
<th align="left">repo</th>
<th align="left">what it is</th>
<th align="left">stack</th>
<th align="center">touched</th>
</tr>
<tr><td>🐠</td><td><a href="https://github.com/Ictio-Biometria"><b>Ictiobiometria</b></a></td><td>fish biometry · field app + cv backend</td><td><sub><code>flutter</code> · <code>python</code> · <code>cv</code></sub></td><td align="center"><code>2025-04</code></td></tr>
<tr><td>👁</td><td><a href="https://github.com/Prism411/JL-EyeTeractive"><b>JL-EyeTeractive</b></a></td><td>cross-platform eye-tracking (mobile + web) via webcam with competitive accuracy</td><td><sub><code>python</code> · <code>opencv</code> · <code>kotlin</code></sub></td><td align="center"><code>2025-01</code></td></tr>
<tr><td>🎮</td><td><a href="https://github.com/Prism411/VIII-Semana-da-Computacao-GAMEDEV-COURSE"><b>VIII Semana · GameDev Course</b></a></td><td>gamedev intro course · I taught it</td><td><sub><code>python</code> · <code>pygame</code></sub></td><td align="center"><code>2025-10</code></td></tr>
<tr><td>🤖</td><td><b>jadent</b> &nbsp;<sub>· private</sub></td><td>personal remote AI terminal hub via Discord, Telegram and web</td><td><sub><code>typescript</code> · <code>docker</code> · <code>discord.js</code></sub></td><td align="center"><code>2026-04</code></td></tr>
<tr><td>🐘</td><td><a href="https://github.com/Prism411/pg_hsmv"><b>pg_hsmv</b></a> &nbsp;<sub>· private</sub></td><td>PostgreSQL C extension for multimedia similarity · visual + audio + semantic descriptors</td><td><sub><code>c</code> · <code>postgresql</code> · <code>docker</code></sub></td><td align="center"><code>2026-04</code></td></tr>
<tr><td>🎰</td><td><a href="https://github.com/Prism411/tigrinho-apostador"><b>tigrinho-apostador</b></a></td><td>sarcastic anti-gambling sim</td><td><sub><code>kotlin</code> · <code>android</code></sub></td><td align="center"><code>2025-09</code></td></tr>
<tr><td>📝</td><td><a href="https://github.com/Prism411/texugo-live-editor-local"><b>texugo-live-editor</b></a></td><td>local LaTeX editor w/ live preview</td><td><sub><code>typescript</code> · <code>docker</code></sub></td><td align="center"><code>2026-03</code></td></tr>
<tr><td>💪</td><td><a href="https://github.com/Prism411/fitHealth-APP"><b>fitHealth-APP</b></a></td><td>habit &amp; exercise tracker</td><td><sub><code>flutter</code> · <code>dart</code></sub></td><td align="center"><code>2025-03</code></td></tr>
<tr><td>🐍</td><td><a href="https://github.com/Prism411/VII-Semana-da-Computa-o---Python-Course"><b>VII Semana · Python Course</b></a></td><td>python intro course · I co-taught it</td><td><sub><code>python</code></sub></td><td align="center"><code>2024-09</code></td></tr>
<tr><td>🧤</td><td><a href="https://github.com/Prism411/hgrs-project"><b>HGRS · luva tradutora libras</b></a></td><td>LIBRAS sign-glove translator (samsung NAVE)</td><td><sub><code>c++</code> · <code>arduino</code></sub></td><td align="center"><code>2024-05</code></td></tr>
</table>

<details>
<summary><b>📦 archived &amp; academic experiments</b> &nbsp;<sub>click to unfold</sub></summary>

<br/>

<table>
<tr>
<td width="65%" valign="top">

<sub>
<code>projectXYZ</code> · <code>luminaPixel-studio</code> (img processing, py, 2024) ·
<code>JASM</code> (asm simulator, java, 2023) · <code>cineCalc</code> (physics, java, 2023) ·
<code>pvpi-project</code> (linear algebra, py, 2023) · <code>jl-calculator</code> (flutter, 2024) ·
<code>JLAutoCraft</code> (java, 2023) · <code>b-tree-jader</code> (c++, 2023) ·
<code>vt-api</code> / <code>vt-web</code> / <code>vt-simulatedAmbient</code> (visage-track stack, 2024-2025) ·
<code>BankSystem-Project</code> · <code>ChessGameProject</code> · <code>idw-website</code> ·
<code>idw-orpgp</code> (ruby, 2024) · early java tracks (2022-2023).
</sub>

</td>
<td width="35%" valign="middle" align="center">

<img src="https://media.giphy.com/media/q1mHcB8wOCWf6/giphy.gif" width="180" alt="cat archivist"/>
<br/>
<sub><code>fig 2.</code> <em>homer reviewing my old commits.</em></sub>

</td>
</tr>
</table>

</details>

<!-- ─────────────────────────  STACK  ───────────────────────────── -->

<h2>▍ stack</h2>

<table>
<tr>
<td valign="top" width="60%">

```text
languages    │  python      ▰▰▰▰▰▰▰▰▰▱     daily driver
             │  typescript  ▰▰▰▰▰▰▰▱▱▱     web · research uis
             │  java        ▰▰▰▰▰▰▱▱▱▱     legacy + android
             │  kotlin      ▰▰▰▰▱▱▱▱▱▱     android-native
             │  c / c++     ▰▰▰▰▰▱▱▱▱▱     embedded · pg ext
             │  go          ▰▰▰▱▱▱▱▱▱▱     small services
             │  c#          ▰▰▰▱▱▱▱▱▱▱     unity
             │  rust        ▰▰▱▱▱▱▱▱▱▱     learning slowly
             │  dart        ▰▰▰▰▱▱▱▱▱▱     flutter

ai / ml      │  pytorch · transformers · sentence-transformers
             │  onnx · gliner · faster-whisper · spacy · networkx
             │  ollama (qwen · llama · gemma) · opencv · sklearn

geo / data   │  postgis · qgis · openlayers · mapbox · leaflet
             │  airflow · dbt · python-geopandas

web          │  next.js 15 · fastapi · django · flask
             │  spring-boot · ruby-on-rails

mobile/game  │  flutter · jetpack-compose · unity · unreal
             │  android-native (java/kotlin)

infra        │  docker · postgres · redis · linux · ssh tunnels
             │  tailscale · github-actions
```

</td>
<td valign="top" width="40%" align="center">

<img src="https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif" width="100%" alt="cat keyboard"/>

<br/><br/>

<sub><code>fig 3.</code> <em>cat performing routine<br/>maintenance on the keyboard layer.<br/>output undefined but committed.</em></sub>

</td>
</tr>
</table>

<!-- ───────────────────────  TELEMETRY  ────────────────────────── -->

<h2>▍ telemetry</h2>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=prism411&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&title_color=d4a574&icon_color=d4a574&text_color=c5cae9&bg_color=0a0e27"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prism411&layout=compact&hide_border=true&langs_count=10&title_color=d4a574&text_color=c5cae9&bg_color=0a0e27"/>

<br/><br/>

<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=prism411&hide_border=true&background=0a0e27&stroke=d4a574&ring=d4a574&fire=d4a574&currStreakLabel=d4a574&currStreakNum=f5e6d3&dates=c5cae9&sideNums=f5e6d3&sideLabels=c5cae9"/>
<img width="49%" src="https://github-profile-trophy.vercel.app/?username=prism411&theme=algolia&no-frame=true&row=2&column=4&margin-w=10&margin-h=10"/>

<br/><br/>

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=prism411&hide_border=true&bg_color=0a0e27&color=d4a574&line=d4a574&point=f5e6d3&area=true&area_color=1a3a5c&title_color=d4a574"/>

</div>

<!-- ─────────────────────────  FIELD  ──────────────────────────── -->

<h2>▍ about</h2>

<table border="0">
<tr>
<td valign="top" width="62%">

<blockquote>
"the rainforest is a graph. every fire-spot a node, every river an edge,<br/>
every researcher a community of one trying to compress the canopy<br/>
into a summary that still smells like ozone after the rain."
</blockquote>

- 🔬 research at the intersection of <b>graphs</b>, <b>NLP</b>, <b>feature extraction</b>, <b>CNNs</b>, <b>transformers</b> and <b>embeddings</b>.
- 🎯 currently obsessing over: graph community detection for video selection · entity-density boosting · DINOv2 as a quality proxy · ASR for low-resource dialects.
- 🏎 outside the terminal: <b>ferrari tifosi</b>, dwarf fortress, factorio, racing sims. F1 sundays are sacred.
- 📚 always reading something about graph theory, cognitive load, or remote sensing.

</td>
<td valign="top" width="38%" align="center">

<img src="https://media.tenor.com/x8v1oNUOmg4AAAAi/love-cat.gif" width="60" alt="pixel cat"/>
<img src="https://media.tenor.com/x8v1oNUOmg4AAAAi/love-cat.gif" width="60" alt="pixel cat"/>
<img src="https://media.tenor.com/x8v1oNUOmg4AAAAi/love-cat.gif" width="60" alt="pixel cat"/>

<br/><br/>

<img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif" width="100%" alt="cat in a box"/>

<sub><code>fig 4.</code> <em>standard production deployment vehicle.</em></sub>

</td>
</tr>
</table>

<!-- ─────────────────────────  CONTACT  ────────────────────────── -->

<h2>▍ signal</h2>

<div align="center">
  <a href="https://www.linkedin.com/in/jáder-louis-37ab942bb"><img src="https://img.shields.io/badge/linkedin-0a0e27?style=for-the-badge&logo=linkedin&logoColor=d4a574"/></a>
  <a href="mailto:jaderlouis@proton.me"><img src="https://img.shields.io/badge/protonmail-0a0e27?style=for-the-badge&logo=protonmail&logoColor=d4a574"/></a>
  <a href="mailto:jader.louis1@gmail.com"><img src="https://img.shields.io/badge/gmail-0a0e27?style=for-the-badge&logo=gmail&logoColor=d4a574"/></a>
  <a href="https://github.com/prism411"><img src="https://img.shields.io/badge/github-0a0e27?style=for-the-badge&logo=github&logoColor=d4a574"/></a>
</div>

<div align="center"><sub>research collabs welcome · paper ideas and dataset pointers appreciated.</sub></div>

---

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=merko"/>

<br/><br/>

<sub><code>this readme · last refactored 2026-04-28 · butantã · são paulo · SP</code></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:d4a574,50:1a3a5c,100:0a0e27&height=80&section=footer&animation=fadeIn"/>

</div>
