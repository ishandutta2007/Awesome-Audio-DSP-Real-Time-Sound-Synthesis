# Awesome-Audio-DSP-Real-Time-Sound-Synthesis

# Top Audio DSP & Real-Time Sound Synthesis Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Web-Based DAWs, Real-Time Synthesis Engines & Self-Hosted Audio Frameworks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Audio DSP & Real-Time Sound Synthesis**. These tools help musicians, producers, and developers create music, process audio, and build real-time synthesis systems—covering everything from browser-based collaborative DAWs to low-level C++ frameworks that power professional plugins and standalone instruments.

**Examples** include BandLab, Soundtrap, Audiotool, LANDR, Splice, SuperCollider, Csound, and JUCE (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted audio workstations, open-source DSP frameworks, and community-driven synthesis engines—ideal for developers building custom instruments, researchers exploring algorithmic composition, and producers seeking full control over their signal chain without subscription lock-in. The open-source landscape is genuinely mature: **SuperCollider** provides a real-time audio server with hundreds of UGens , **JUCE** powers a vast ecosystem of commercial plugins , and **openDAW** brings a full DAW into the browser with source code you can inspect .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[BandLab](https://www.bandlab.com/)**  
  Browser-based collaborative DAW with virtual instruments, loop library, and mobile apps. The **zero-commitment entry point** for beginners, operating entirely in the browser without installation . Free tier available; positioned for mobile and experimental creation .

- **[Soundtrap (Spotify)](https://www.soundtrap.com/)**  
  Online cross-platform DAW for browsers. **Premium: $11.99/month or $144/year** . Positioned for indie and education markets, with Spotify backing .

- **[Audiotool](https://www.audiotool.com/)**  
  Advanced collaborative browser DAW with synthesizers, samplers, mixers, and effects. Built for real-time online music production .

- **[LANDR](https://www.landr.com/)**  
  AI mastering platform. **Free (2 songs)**, **Studio: $14.99/month** (unlimited mastering), **Pro: $24.99/month** (stem mastering). Average mastering time: 1–3 minutes. Includes distribution and sample library .

- **[Splice](https://splice.com/)**  
  Sample library subscription. **Sounds: $9.99/month or $120/year** . Integrates with major DAWs for loop and sample discovery .

- **[Waves Creative Access](https://www.waves.com/)**  
  Plugin subscription with 200+ plugins. **$14.99–$24.99/month** . One of the largest commercial plugin collections available by subscription [citation:5][citation:10].

- **[iZotope Music Production Suite Pro](https://www.izotope.com/)**  
  Subscription including Ozone, Neutron, RX, and Nectar. **$20/month or $200/year** [citation:5].

- **[Native Instruments Komplete Now](https://www.native-instruments.com/)**  
  Starter NI library subscription. **$12.50/month** [citation:5].

## Open-Source GitHub Projects

- **[SuperCollider](https://github.com/supercollider/supercollider)**  
  **Platform for audio synthesis and algorithmic composition** with **5,387+ stars** . **scsynth**: real-time audio server with hundreds of UGens for analysis, synthesis, and processing. **sclang**: interpreted language controlling the server. **scide**: editor with integrated help. Supports Windows, macOS, Linux, Raspberry Pi, Bela, and WebAssembly. **GPL-3.0** . Active weekly development .

- **[JUCE](https://github.com/juce-framework/JUCE)**  
  **Comprehensive C++ audio framework** for building cross-platform audio applications, plugins, and high-performance UIs . **2,215+ stars** . Single codebase for desktop and mobile; supports VST3, AU, AAX, and standalone formats. Powers a vast ecosystem of commercial plugins . **License**: AGPL/commercial dual licensing.

- **[Csound](https://github.com/csound/csound)**  
  **Main repository for Csound**, a sound and music computing system. **1,212+ stars** . Supports algorithmic composition, real-time synthesis, and signal processing. Available as standalone, library, or plugin framework .

- **[Pure Data](https://github.com/pure-data/pure-data)**  
  **Free real-time computer music system** with **1,914+ stars** . Visual programming environment for audio synthesis and processing. **Pd-l2ork** and **Purr Data** are actively maintained variants .

- **[openDAW](https://github.com/andremichelle/openDAW)**  
  **Next-generation web-based DAW** with **2,436+ stars** . Browser-native digital audio workstation built with modern web technologies. Active development .

- **[Zrythm](https://github.com/zrythm/zrythm)**  
  **Highly automated and intuitive DAW** with **3,197+ stars** . Full-featured digital audio workstation for professional music production. Active weekly development .

- **[Faust](https://github.com/grame-cncm/faust)**  
  **Functional programming language for signal processing and sound synthesis** with **2,931+ stars** . Compiles to multiple targets including C++, WebAssembly, and plugins. Designed for real-time audio DSP .

- **[VCV Rack](https://github.com/VCVRack/Rack)**  
  **The virtual Eurorack studio** with **4,017+ stars** . Open-source modular synthesizer platform with hundreds of community modules. Standalone and VST/AU plugin versions .

- **[Surge Synthesizer](https://github.com/surge-synthesizer/surge)**  
  **Free and open-source hybrid synthesizer** with **4,115+ stars** . Originally released by Vember Audio; now community-maintained. VST3, AU, and CLAP formats .

- **[Ardour](https://github.com/Ardour/ardour)**  
  **Full-featured DAW for Linux, macOS, and Windows** with **5,417+ stars** . Professional-grade multitrack recording, editing, and mixing. GPL-2.0 licensed .

- **[HISE](https://github.com/christophhart/HISE)**  
  **Open-source framework for sample-based instruments** with **1,448+ stars** . Build sample libraries and virtual instruments without writing C++ from scratch .

- **[nih-plug](https://github.com/robbert-vdh/nih-plug)**  
  **Rust VST3 and CLAP plugin framework** with **3,033+ stars** . Modern alternative to JUCE for Rust developers building audio plugins .

### Additional Strong Open-Source Options

- **[ComposeYogi](https://alternativeto.net/software/fl-studio/?platform=online)** — Free, open-source (MIT) music composition tool for beat-making, loops, and arrangements. Built with Web Audio and WASM. Available as SaaS, self-hosted, or Docker [citation:2].
- **[Helm](https://github.com/mtytel/helm)** — Free polyphonic synth with lots of modulation (2,469+ stars) [citation:1].
- **[ZynAddSubFX](https://github.com/zynaddsubfx/zynaddsubfx)** — Open-source synthesizer (1,096+ stars) [citation:1].
- **[STK (Synthesis ToolKit)](https://github.com/thestk/stk)** — C++ audio signal processing and algorithmic synthesis classes (1,171+ stars) [citation:1].
- **[JUCE-based openDAW](https://github.com/glenwrhodes/OpenDaw)** — Free, open-source DAW for Windows with Qt 6 UI and VST3 support [citation:12].
- **[GridSound](https://github.com/gridsound/daw)** — Browser-based DAW following Web Audio API (1,894+ stars) [citation:12].
- **[DawDreamer](https://github.com/DBraun/DawDreamer)** — Python DAW with VST support and FAUST integration (1,348+ stars) [citation:12].

**Frameworks for building custom systems**: Combine **JUCE** for cross-platform plugin development, **SuperCollider** or **Csound** for algorithmic composition and synthesis, and **Faust** for DSP prototyping that compiles to multiple targets. For browser-based work, **openDAW** and **GridSound** provide Web Audio foundations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Audio DSP and synthesis tools can produce high sound pressure levels; protect your hearing and use appropriate monitoring levels. Real-time audio processing requires low-latency system configuration.
- **Subscription fatigue is real in audio software.** **Waves, iZotope, and Native Instruments all offer perpetual licenses alongside subscriptions**, but update pricing has become more aggressive . **LANDR's AI mastering is convenient but criticized for producing "average" sound**—professional mastering still costs $200–$1,000 per track . **Open-source alternatives eliminate subscription costs but require technical investment**: SuperCollider and Csound have steep learning curves, JUCE requires C++ expertise, and self-hosted DAWs need system administration. Validate whether you need a polished SaaS workflow (LANDR, Splice) or full control over your signal chain (SuperCollider, JUCE) before committing.

---

**Made for musicians, audio developers, and researchers building sound synthesis infrastructure.**  
Let's make audio DSP and real-time synthesis more open, expressive, and artist-controlled.
