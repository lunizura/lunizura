<div align="center">
  <img src="assets/header.svg?v=6" width="100%" alt="lunizura: Ronova Sky Rift and Crimson Black Hole" />
</div>

## About

Undergraduate Computer Science student at **Universitas Sebelas Maret (UNS)**, focusing on systems programming, binary analysis, process memory forensics, and 3D asset engineering.

Active learner, driven by curiosity about how software works beneath the surface: from decompiling proprietary game archives and tracking runtime heap memory structures, to building standalone glTF 3D pipelines and interactive open-data tools. Always open to code reviews, constructive feedback, and collaborative projects.

---

## Featured Engineering Projects

### [uma-chibi-re: Umamusume Chibi 3D RE & glTF Pipeline](https://github.com/lunizura/uma-chibi-re)
> **Stack:** Python 3.10+ • NumPy • UnityPy • CTypes • SQLiteMC • glTF 2.0

An offline reverse engineering suite and modular glTF 2.0 3D asset extraction pipeline targeting game client archives:
- **AES-256 SQLite Database Decryption:** Uses raw Windows C-runtime bindings (`sqlite3mc_x64.dll`) to decrypt PBKDF2 HMAC-SHA1 secured database manifests.
- **Vectorized Rolling XOR Engine:** Decrypts encrypted Unity bundles with an 88-byte keystream cycle, accelerated 73.8x using NumPy vectorization.
- **Standalone glTF 2.0 Binary Compiler:** Custom-built `.glb` compiler that serializes binary buffer views, accessors, materials, and skeletal hierarchies without third-party 3D engines.
- **Anatomical Assembly & Alpha Blending:** Automatically calculates skeletal attachment matrices ($Y = 0.4963\text{ m}$ neck, $Y = 0.3053\text{ m}$ tail) and assigns transparent alpha blending (`alphaMode: BLEND`) to facial expression submeshes.

---

### [fm26-stat-modifier: Football Manager 26 Tactical Scout & Memory Engine](https://github.com/lunizura/fm26-stat-modifier)
> **Stack:** Python 3.10+ • Win32 API (`ReadProcessMemory` / `WriteProcessMemory`) • Zstandard • CustomTkinter

A live Windows process memory editor and save-game database parser for Football Manager 26:
- **Direct Process Memory Manipulation:** Resolves multi-level dynamic pointer chains to read and patch live player attribute structures (`ACTUAL_PLAYER@db`) at runtime.
- **Save Stream Decompression:** Zstandard stream decompression engine indexing 46,500+ players and 988,000+ name dictionary entries in under 0.15 seconds.
- **Attribute Scale Translation:** Automatically converts front-end display ratings (1-20) to internal binary values (5-100 at offset `+0x15F`).
- **Tactical Telemetry GUI:** Modern desktop interface with one-click attribute preset boosting and live memory validation.

---

### [keketatan-univ-indonesia: Admissions Intelligence & Risk Simulator](https://github.com/lunizura/keketatan-univ-indonesia)
> **Stack:** Vanilla JavaScript • Open Data Architecture • GitHub Pages  
> **Live Demo:** [lunizura.github.io/keketatan-univ-indonesia](https://lunizura.github.io/keketatan-univ-indonesia/)

An interactive admissions analytics platform and risk calibration simulator covering 50 premier Indonesian universities (35 PTN & 15 PTS):
- **National Selectivity Leaderboard:** Real-time quota allocations, historical applicant volumes, and 3-year competitiveness trajectories.
- **Choice Risk Simulator:** Dual-track heuristic algorithm evaluating admission risk across SNBP and SNBT examination tracks.
- **Zero Heavy Dependencies:** Lightweight client-side engine with instantaneous search and bilingual localization (ID / EN).

---

## Technical Skills & Toolchain

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, C++20, C (Systems), JavaScript, SQL, PowerShell |
| **Systems & Reverse Engineering** | Win32 API, Windows Internals, Process Memory Editing, Ghidra SRE, x64dbg, Cheat Engine |
| **3D Graphics & Assets** | Blender Studio (Stylized Modeling, UV/Topology), glTF 2.0 Binary Compiler, Unity Asset Extraction |
| **Development & Tooling** | Git, GitHub Actions, Node.js, HTML5, CSS3, Visual Studio |

---

## Open Data Campus Modules

Individual higher education dataset modules maintained under the open data initiative:

| Repository | Scope & Description | Live Explorer |
| :--- | :--- | :---: |
| [`ui-prodi-directory`](https://github.com/lunizura/ui-prodi-directory) | Universitas Indonesia study programs, quota allocations, and accreditation dataset | [Live Demo](https://lunizura.github.io/ui-prodi-directory/) |
| [`itb-prodi-directory`](https://github.com/lunizura/itb-prodi-directory) | Institut Teknologi Bandung TPB faculty admission models and international accreditations | [Live Demo](https://lunizura.github.io/itb-prodi-directory/) |
| [`ugm-prodi-directory`](https://github.com/lunizura/ugm-prodi-directory) | Universitas Gadjah Mada academic directory, degree levels, and intake matrix | [Live Demo](https://lunizura.github.io/ugm-prodi-directory/) |
| [`uns-prodi-directory`](https://github.com/lunizura/uns-prodi-directory) | Universitas Sebelas Maret program accreditation and entrance capacity records | [Live Demo](https://lunizura.github.io/uns-prodi-directory/) |

---

<div align="center">
  <img src="assets/footer.svg?v=3" width="100%" alt="lunizura Crimson Horizons" />
</div>
