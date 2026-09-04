<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1DB954,10B981,059669,047857&height=220&section=header&text=Hey%20there,%20I'm%20Gilzone%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Embedded%20Systems%20•%20Edge%20AI%20•%20Hardware%20Preservation%20•%20Android%20%26%20Systems&descAlignY=62&descSize=18&descColor=e0e7ff" width="100%" alt="Header Banner" />
</div>

<p align="center">
  <a href="https://github.com/Gilzone?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/Gilzone?style=for-the-badge&color=1DB954&logo=github&label=Total%20Stars" alt="Total Stars" /></a>
  <a href="https://github.com/Gilzone?tab=followers"><img src="https://img.shields.io/github/followers/Gilzone?style=for-the-badge&color=059669&logo=github&label=Followers" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/Focus-Embedded%20%26%20Edge%20AI-blueviolet?style=for-the-badge" alt="Focus" />
  <img src="https://img.shields.io/badge/Philosophy-Zero%20E--Waste-orange?style=for-the-badge" alt="Philosophy" />
</p>

<p align="center">
  <em>"Turning abandoned and resource-constrained hardware into independent, standalone tools, consoles, and edge intelligence engines."</em>
</p>

---

## ⚡ About Me

I specialize in **hardware reverse-engineering, embedded Linux, edge AI optimization, and lightweight mobile tooling**. My core passion is rescuing deprecated, low-power, and end-of-life electronics (like the Spotify Car Thing and low-cost micro-SBCs) and engineering zero-dependency software that runs **100% locally and offline** directly on the metal.

* 🔭 **Currently Building:** Complete standalone operating environments, custom launchers, and x86 virtualization for embedded ARM devices.
* 🧠 **Edge AI Focus:** Squeezing quantized LLMs (SmolLM2, Qwen2.5, TinyDolphin) into sub-512MB RAM architectures via kernel swap, zram, and Ollama/llama.cpp tuning.
* 📱 **Mobile & Tooling:** Building zero-bloat Android runtimes to convert any local HTML/canvas project into immersive native mobile apps.
* ⚙️ **Systems Philosophy:** Zero host-PC dependencies, zero mandatory cloud servers, and true offline ownership.

---

## 🚀 Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏎️ <a href="https://github.com/Gilzone/carthing-apps">Spotify Car Thing — Standalone OS Suite</a></h3>
      <p><em>Turned the discontinued Spotify Car Thing into an independent offline handheld console, e-reader, voice recorder, and x86 virtual PC with zero server/host PC dependencies.</em></p>
      <p align="center">
        <a href="https://github.com/Gilzone/carthing-apps">
          <img src="https://raw.githubusercontent.com/Gilzone/carthing-apps/main/docs/screenshots/launcher_games.png" width="100%" alt="Car Thing 3D Launcher Preview" style="border-radius: 8px; border: 1px solid #334155;" />
        </a>
      </p>
      <ul>
        <li>⚡ <b>1-Click Installer:</b> Automated device detection, bootloader driver setup, and SCP synchronization.</li>
        <li>🌐 <b>On-Device Neural Translator:</b> 100% offline Bergamot/Marian NMT WASM edge-AI translator with direct-disk loading (&lt;0.2s), instant bidirectional English ↔ Spanish swapping, and hardware-debounced touch keyboard.</li>
        <li>🎮 <b>23 Games:</b> Unbundled assets dropping HTML game load times by 95% (20s &rarr; &lt;1s).</li>
        <li>🖥️ <b>KolibriOS x86 VM:</b> Touchpad mouse emulation and custom on-screen virtual keyboard.</li>
        <li>🎙️ <b>ALSA Dual-Link Audio:</b> Bypassed wake-word daemon locks to enable local voice memos.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Linux-7.0.2_ARM64-FCC624?style=flat-square&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/Amlogic-S905D2-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/AI-Marian_NMT_WASM-3b82f6?style=flat-square" />
        <img src="https://img.shields.io/badge/x86-v86_WASM-purple?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/Gilzone/Installing-a-LLM-on-Raspberry-Pi-Zero-2-W">Edge LLMs on a $15 Pi Zero 2 W</a></h3>
      <p><em>Architectural guide and benchmark suite proving generative LLMs can run locally and privately on a $15 board with only 512MB of RAM.</em></p>
      <p align="center">
        <a href="https://github.com/Gilzone/Installing-a-LLM-on-Raspberry-Pi-Zero-2-W">
          <img src="https://raw.githubusercontent.com/Gilzone/Installing-a-LLM-on-Raspberry-Pi-Zero-2-W/main/docs/terminal_demo.svg" width="100%" alt="Pi Zero 2 W LLM Terminal Demo" style="border-radius: 8px; border: 1px solid #334155;" />
        </a>
      </p>
      <ul>
        <li>📊 <b>Memory Budgeting:</b> Precision OS stripping keeping base Linux idle at ~45 MB RAM.</li>
        <li>⚡ <b>Quantized Inference:</b> Running SmolLM2 135M at 3.2–5.5 tokens/sec via Ollama ARM64.</li>
        <li>🔧 <b>Kernel Tuning:</b> Swap file sizing, swappiness algorithms, and thermal overvoltage management.</li>
        <li>🌐 <b>Local REST API:</b> Self-hosted AI endpoint accessible across the local network.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Raspberry_Pi-Zero_2_W-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white" />
        <img src="https://img.shields.io/badge/Inference-Ollama-black?style=flat-square&logo=ollama&logoColor=white" />
        <img src="https://img.shields.io/badge/Model-SmolLM2_135M-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/RAM-512MB_Optimized-success?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📱 <a href="https://github.com/Gilzone/html-open">HTMLOpen — Fullscreen HTML App Runner</a></h3>
      <p><em>Zero-bloat (&lt;450 KB) native Android container running any local HTML file, game, or webapp in true immersive fullscreen with universal file permissions.</em></p>
      <p align="center">
        <a href="https://github.com/Gilzone/html-open">
          <img src="https://raw.githubusercontent.com/Gilzone/html-open/main/docs/htmlopen_preview.svg" width="100%" alt="HTMLOpen Preview" style="border-radius: 8px; border: 1px solid #334155;" />
        </a>
      </p>
      <ul>
        <li>📱 <b>Sticky Immersive Mode:</b> Hides status bar and navigation bar with zero gesture interference.</li>
        <li>🔓 <b>Universal <code>file://</code> Access:</b> Loads multi-file games, scripts, textures, and WASM.</li>
        <li>⚡ <b>Pure Native:</b> Zero ads, zero tracking, hardware accelerated, and under 500 KB.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Android-5.0+-3DDC84?style=flat-square&logo=android&logoColor=white" />
        <img src="https://img.shields.io/badge/APK_Size-~445_KB-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Language-Java-ED8B00?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>💬 <a href="https://github.com/Gilzone/messager">Messager — Real-Time Room Chat</a></h3>
      <p><em>Lightweight, self-hosted real-time chat with 5-digit room PINs, instant clipboard image sharing, and single-file standalone binaries built for zero-dependency deployment.</em></p>
      <p align="center">
        <a href="https://github.com/Gilzone/messager">
          <img src="https://raw.githubusercontent.com/Gilzone/messager/main/docs/messager_ui.svg" width="100%" alt="Messager UI Preview" style="border-radius: 8px; border: 1px solid #334155;" />
        </a>
      </p>
      <ul>
        <li>⚡ <b>Socket.io Real-Time:</b> Instant messaging with zero server storage overhead.</li>
        <li>📦 <b>Standalone Binaries:</b> Packaged with <code>pkg</code> into portable single-file executables.</li>
        <li>📸 <b>Rich Media:</b> Paste images directly from clipboard (Ctrl+V) or upload photos.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Node.js-18+-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Socket.io-4.x-black?style=flat-square&logo=socketdotio&logoColor=white" />
        <img src="https://img.shields.io/badge/Packaging-pkg_Binaries-blueviolet?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" width="100%" valign="top">
      <h3>🎙️ <a href="https://github.com/Gilzone/pi-zero-voice-ai">Pi Zero Voice AI — 100% Offline Voice Assistant on 512 MB RAM</a></h3>
      <p><em>Fully localized edge voice AI on a $15 Raspberry Pi Zero 2 W running Whisper.cpp STT, SmolLM2-360M LLM, and Flite TTS inside 512MB RAM with zero swap thrashing.</em></p>
      <p align="center">
        <a href="https://github.com/Gilzone/pi-zero-voice-ai">
          <img src="https://raw.githubusercontent.com/Gilzone/pi-zero-voice-ai/main/assets/terminal_screenshot.png" width="100%" alt="Pi Zero Voice AI Preview" style="border-radius: 8px; border: 1px solid #334155;" />
        </a>
      </p>
      <ul>
        <li>⚡ <b>Complete Voice Loop:</b> Audio In &rarr; Whisper STT &rarr; SmolLM2-360M LLM &rarr; Flite TTS Speech Out.</li>
        <li>🧠 <b>512MB RAM Budget:</b> Sequential lifecycle peaking at ~267 MB RAM (0 KB swap thrashing).</li>
        <li>🎙️ <b>Native 16 kHz Audio:</b> Flite unit-selection eliminating synthetic buzz and resampling delay.</li>
        <li>📊 <b>100% Factual Accuracy:</b> Benchmark suite with 10 real-world factual questions answered correctly.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Raspberry_Pi-Zero_2_W-C51A4A?style=flat-square&logo=raspberry-pi&logoColor=white" />
        <img src="https://img.shields.io/badge/STT-Whisper.cpp-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/LLM-SmolLM2_360M-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/TTS-Flite_16kHz-green?style=flat-square" />
        <img src="https://img.shields.io/badge/RAM-512MB_Zero_Swap-success?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 🧰 Technical Arsenal

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%"><b>Hardware & Embedded</b></td>
      <td align="center" width="25%"><b>Languages & Systems</b></td>
      <td align="center" width="25%"><b>AI & Inference</b></td>
      <td align="center" width="25%"><b>Mobile & Tooling</b></td>
    </tr>
    <tr>
      <td valign="top">
        • Amlogic (S905D2 / Superbird)<br>
        • Raspberry Pi (Zero 2 W, 3, 4)<br>
        • ARM64 / AArch64 Linux<br>
        • U-Boot & Bootloaders<br>
        • ALSA & Sound Architecture<br>
        • Weston / Wayland Compositors
      </td>
      <td valign="top">
        • Python (3.10+ / Automation)<br>
        • C / C++ (Low-Level Systems)<br>
        • Java (Android Native SDK)<br>
        • Bash / POSIX Shell<br>
        • PowerShell Core<br>
        • JavaScript (ESNext / Node.js)
      </td>
      <td valign="top">
        • Ollama (ARM64 Optimization)<br>
        • llama.cpp & GGUF Quantization<br>
        • SmolLM2 & Micro-Architectures<br>
        • Linux Swap & zram Tuning<br>
        • Edge AI REST APIs<br>
        • TinyML Principles
      </td>
      <td valign="top">
        • Android Immersive WebView<br>
        • WebAssembly (WASM)<br>
        • Socket.io & WebSockets<br>
        • Express.js<br>
        • Standalone Packaging (`pkg`)<br>
        • Chrome DevTools Protocol (CDP)
      </td>
    </tr>
  </table>
</div>

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Gilzone&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Gilzone GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Gilzone&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="48%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gilzone&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="60%" />
</p>

---

<div align="center">
  <p><b>“Resurrecting hardware, pushing micro-architectures, and keeping technology out of landfills.”</b></p>
  <p>Feel free to star ⭐ repositories, open discussions, or collaborate on embedded/edge projects!</p>
</div>
