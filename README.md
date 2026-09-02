<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1DB954,10B981,059669,047857&height=220&section=header&text=Hey%20there,%20I'm%20Gilzone%20👋&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Embedded%20Systems%20•%20Edge%20AI%20•%20Hardware%20Preservation%20•%20Systems%20Software&descAlignY=62&descSize=18&descColor=e0e7ff" width="100%" alt="Header Banner" />
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

I specialize in **hardware reverse-engineering, embedded Linux, and edge AI optimization**. My core passion is rescuing deprecated, low-power, and end-of-life electronics (like the Spotify Car Thing and low-cost micro-SBCs) and engineering zero-dependency software that runs **100% locally and offline** directly on the metal.

* 🔭 **Currently Building:** Complete standalone operating environments, custom launchers, and x86 virtualization for embedded ARM devices.
* 🧠 **Edge AI Focus:** Squeezing quantized LLMs (SmolLM2, Qwen2.5, TinyDolphin) into sub-512MB RAM architectures via kernel swap, zram, and Ollama/llama.cpp tuning.
* ⚙️ **Systems Philosophy:** Zero host-PC dependencies, zero mandatory cloud servers, and true offline ownership.

---

## 🚀 Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏎️ <a href="https://github.com/Gilzone/carthing-apps">Spotify Car Thing — Standalone OS Suite</a></h3>
      <p><em>Turned the discontinued Spotify Car Thing into an independent offline handheld console, e-reader, voice recorder, and x86 virtual PC with zero server/host PC dependencies.</em></p>
      <ul>
        <li>⚡ <b>1-Click Installer:</b> Automated device detection, bootloader driver setup, and SCP synchronization.</li>
        <li>🎮 <b>23 Games:</b> Unbundled assets dropping HTML game load times by 95% (20s &rarr; &lt;1s).</li>
        <li>🖥️ <b>KolibriOS x86 VM:</b> Touchpad mouse emulation and custom on-screen virtual keyboard.</li>
        <li>🎙️ <b>ALSA Dual-Link Audio:</b> Bypassed wake-word daemon locks to enable local voice memos.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Linux-7.0.2_ARM64-FCC624?style=flat-square&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/Amlogic-S905D2-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/Wayland-Weston-red?style=flat-square" />
        <img src="https://img.shields.io/badge/x86-v86_WASM-purple?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/Gilzone/Installing-a-LLM-on-Raspberry-Pi-Zero-2-W">Edge LLMs on a $15 Pi Zero 2 W</a></h3>
      <p><em>Architectural guide and benchmark suite proving generative LLMs can run locally and privately on a $15 board with only 512MB of RAM.</em></p>
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
    <td colspan="2" valign="top">
      <h3>💬 <a href="https://github.com/Gilzone/messager">Messager — Ephemeral Room Chat & Standalone Binaries</a></h3>
      <p><em>Lightweight, self-hosted real-time chat with 5-digit room PINs, instant clipboard image sharing, and single-file standalone binaries built for zero-dependency deployment.</em></p>
      <p>
        <img src="https://img.shields.io/badge/Node.js-18+-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/Socket.io-4.x-black?style=flat-square&logo=socketdotio&logoColor=white" />
        <img src="https://img.shields.io/badge/Packaging-pkg_Binaries-blueviolet?style=flat-square" />
        <img src="https://img.shields.io/badge/Privacy-Self_Hosted-brightgreen?style=flat-square" />
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
      <td align="center" width="25%"><b>Web & Tooling</b></td>
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
        • Bash / POSIX Shell<br>
        • PowerShell Core<br>
        • JavaScript (ESNext / Node.js)<br>
        • Assembly (x86 / KolibriOS)
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
        • WebAssembly (WASM)<br>
        • Socket.io & WebSockets<br>
        • Express.js<br>
        • Chrome DevTools Protocol (CDP)<br>
        • Single-File Packaging (`pkg`)<br>
        • Git & GitHub CLI Tooling
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
