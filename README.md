<h1 align="center">Hey, I'm Ryan 👋</h1>

<p align="center">
  <b>Software engineer in Texas. I build local-first tools for creators and AI agents:</b><br>
  game character pipelines, audio and video editors, voice, and developer tooling.
</p>

<p align="center">
  <a href="https://dashwood.net/"><img alt="Website" src="https://img.shields.io/badge/dashwood.net-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/ryan-stefan-austin"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/dashwizzle"><img alt="X" src="https://img.shields.io/badge/@dashwizzle-000000?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="Svelte" src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white">
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
  <img alt="Three.js" src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white">
  <img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white">
  <img alt="Tauri" src="https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white">
  <img alt="Blender" src="https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white">
</p>

## Featured projects

Everything here runs on your own machine. No accounts, no cloud round trips.

<table>
  <tr>
    <td colspan="2" align="center">
      <a href="https://github.com/dashw00d/rigsmith"><img src="https://raw.githubusercontent.com/dashw00d/rigsmith/main/docs/screenshots/motion-huntress-bow-release.webp" alt="Rigsmith: a character drawing a bow, with the skeleton overlay and an animation timeline showing a Release sound event" width="760"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/rigsmith">Rigsmith</a> · character pipeline for games</h3>
      Auto-rig 3D character meshes onto the Mixamo skeleton, paint skin weights, fit gear, retarget 2,446 Mixamo clips and export game-ready GLB units, with sound events, bow draws and mounted riders.
      <br><sub>TypeScript · Svelte · Three.js · Blender</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/speechedit"><img src="https://raw.githubusercontent.com/dashw00d/speechedit/main/docs/screenshots/transcript-editor.png" alt="SpeechEdit: a video transcript where selected words are deleted to cut the video" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/speechedit">SpeechEdit</a></h3>
      Edit video by deleting words from a Whisper transcript. Strips filler words, silence and retakes, adds captions, exports with FFmpeg. Desktop and browser, with an MCP server.
      <br><sub>TypeScript · Electron · Whisper · FFmpeg</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/TapComposer"><img src="https://raw.githubusercontent.com/dashw00d/TapComposer/main/docs/screenshots/02-song-workspace.png" alt="TapComposer: a multi-track song workspace with a clip playlist" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/TapComposer">TapComposer</a></h3>
      Hum or tap a melody and get an editable multi-track song. On-device pitch detection (CREPE on ONNX), automatic chords, bass and drums, WAV, MP3 and MIDI export.
      <br><sub>TypeScript · Next.js · Web Audio</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/sound-lab"><img src="https://raw.githubusercontent.com/dashw00d/sound-lab/main/docs/screenshots/sounds-page.png" alt="Sound Lab: prompt variants, takes, votes and a waveform player" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/sound-lab">Sound Lab</a></h3>
      Generate game sound effects and adaptive music locally with Stable Audio 3. Audition and vote on takes in a web app, build alert families, balance the mix, ship the winners.
      <br><sub>Python · React · Stable Audio</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/lantern2"><img src="https://raw.githubusercontent.com/dashw00d/lantern2/main/docs/screenshots/dashboard-dark.png" alt="Lantern: a web control center listing dev servers with start, stop and logs" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/lantern2">Lantern</a></h3>
      Local dev server manager for Linux. Start, stop and watch every dev server from a web control center, a CLI or an AI agent over MCP. Run any git branch beside main on its own port.
      <br><sub>Rust · systemd · Tauri · MCP</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/live-gallery"><img src="https://raw.githubusercontent.com/dashw00d/live-gallery/main/docs/screenshots/gallery.png" alt="Live Gallery: a grid of images and 3D models with NEW badges on files that just appeared" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/live-gallery">Live Gallery</a></h3>
      Watch a folder and see every new image or 3D model in your browser the moment it's saved. Handy for following AI agent, render or export output.
      <br><sub>Python (stdlib only) · Rust · Three.js</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <a href="https://github.com/dashw00d/jimmy"><img src="https://raw.githubusercontent.com/dashw00d/jimmy/main/docs/screenshots/cli-say-transcribe.png" alt="Jimmy: a terminal session where say writes a WAV file and transcribe reads it back" width="400"></a>
      <br>
      <h3><a href="https://github.com/dashw00d/jimmy">Jimmy</a></h3>
      An offline voice gateway in Rust: speech-to-text, text-to-speech and a "Hey Jimmy" wake word. Use it as a CLI, WebSocket/HTTP server or library, and hook it up to Claude Code, Codex or Ollama.
      <br><sub>Rust · WebAssembly · ONNX</sub>
    </td>
  </tr>
</table>

## Also on my bench

| Project | What it does |
|---|---|
| [**realfly**](https://github.com/dashw00d/realfly) | A fruit fly on your desktop, driven by a live FlyWire connectome simulation (Electron + Three.js) |
| [**orchestrator-next**](https://github.com/dashw00d/orchestrator-next) | Event-driven multi-agent workflow orchestrator that dispatches roles via Claude Code, Codex, OpenCode or a direct LLM API |
| [**no-nonsense-orchestration**](https://github.com/dashw00d/no-nonsense-orchestration) | Autonomous AI agent orchestration with a single cron job and a SQLite task board |
| [**go-ask-a-stranger**](https://github.com/dashw00d/go-ask-a-stranger) | MCP server for anonymous Q&A roulette |
| [**coolify-migration-kit**](https://github.com/dashw00d/coolify-migration-kit) | Templates and a runbook for moving a PHP 8.3 + SQLite Laravel app from a traditional host to a Coolify VPS, ~1 minute deploys |
| [**ipex-from-scratch**](https://github.com/dashw00d/ipex-from-scratch) | Clean-room reconstruction and port scaffold of IPEX monolithic decode kernels |

## About me

I've spent the last several years as the sole engineer behind production web systems for small businesses: hosting, data pipelines, automation and the apps people actually use every day. A few results from that work:

- Turned 15 years of staffing records into marketing intelligence behind a **20x** campaign lift
- Moved a WordPress site to a custom platform and cut load time from **~9s to 0.8s**
- Raised email inbox delivery from **60% to 98%**
- Scaled a crawler fleet to **50 cloud workers** and cut stuck jobs by **90%+**

The open-source projects above are my side projects.

## Work with me

Need a website, a custom app or an automation that saves your team hours? I take fixed-fee projects through **[dashwood.net](https://dashwood.net/)**.
