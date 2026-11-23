<div align="center">
  <img src="assets/header.svg?v=6" width="100%" alt="lunizura: Ronova Sky Rift and Crimson Black Hole" />
</div>

## About

Undergraduate Computer Science student at **Universitas Sebelas Maret (UNS)** focused on **cybersecurity, reverse engineering, systems programming (C / C++20), Windows process internals, and binary asset pipelines**.

Driven by understanding software below the abstraction layer—from reversing undocumented binary file formats and inspecting live Win32 memory structures to building zero-dependency C++20 engines, standalone glTF 2.0 compilers, and civic open-data tools.

---

## Featured Engineering Projects

### [digital-works-compiler: Digital Works (`.dwm`) Binary Spec & Circuit Compiler](https://github.com/lunizura/digital-works-compiler)
> **Stack:** Python 3.10+ (Zero Dependencies) • Delphi VCL Binary RE • Pytest (226 Tests)

A reverse-engineered byte-level specification and pure-Python schematic compiler for Digital Works 3.0 `.dwm` files:
- **Proprietary Format Specification (`DWM_FORMAT.md`):** Documented Borland Delphi VCL `TWriter`/`TSerializeWriter` object-graph streams (`04 dd c4 22 00` header) from 20 calibration seed circuits.
- **Orthogonal Manhattan Wire Router & ASCII Preview:** Computes exact pin offsets, routes 90-degree Z/L channels, and previews circuits directly in the terminal.
- **Multi-Tier Verification:** 226 automated tests across Python `3.10–3.13` covering E2E circuits and white-box adversarial invariants.

---

### [uma-chibi-re: Umamusume Chibi 3D RE & glTF 2.0 Pipeline](https://github.com/lunizura/uma-chibi-re)
> **Stack:** Python 3.10+ • NumPy • UnityPy • C-FFI (`sqlite3mc_x64.dll`) • glTF 2.0 • CustomTkinter

An offline reverse-engineering suite and modular `.glb` extraction studio for game client archives:
- **AES-256-CBC SQLite Decryption:** Decrypts local `meta` catalogs via C-FFI bindings to SQLite3MultipleCiphers.
- **Vectorized Rolling XOR Engine:** NumPy-accelerated 88-byte keystream decryption (**73.8x speedup**, 19.4 ms per 5 MB bundle).
- **Standalone Binary glTF 2.0 Compiler:** Serializes buffers, accessors, skeletal nodes, and alpha-blended facial submeshes into Khronos-compliant `.glb` containers with a portable Windows studio executable (`v1.1.0`).

---

### [omnisbelli: Zero-Dependency C++20 Planetary Siege Engine](https://github.com/lunizura/omnisbelli)
> **Stack:** Modern C++20 • CMake • Win32 DIB Software Rasterizer • Clang ASan/UBSan

A macro-scale planetary attrition simulator and retro 640×360 software-rendered command cogitator:
- **Lanchester & Monte Carlo Combat Engine:** Simulates 100M+ entities via Square vs. Linear chokepoint attrition, synaptic cohesion graphs, munitions depletion, and 9 pluggable `IFactionRuleModule` rule engines.
- **Custom Software Pixel Pipeline:** Zero-dependency Win32 DIBSection framebuffer with Bayer 4×4 dithering, embedded bitmap glyphs, CRT scanline shaders, and integer nearest-neighbor scaling.
- **Cross-Platform Verified:** 34 C++20 engine test suites verified under both MSVC (Windows) and Clang ASan+UBSan (Ubuntu).

---

### [fm26-stat-modifier: Football Manager 26 Memory Engine & Tactical Scout](https://github.com/lunizura/fm26-stat-modifier)
> **Stack:** Python 3.10+ • Win32 API (`ReadProcessMemory` / `WriteProcessMemory`) • Zstandard • CustomTkinter

A live Windows process memory editor and `.fm` save-stream parser for Football Manager 26:
- **Runtime Struct Resolution:** Scans `ACTUAL_PLAYER@db` C++ objects in `fm.exe` to read/patch 54 attributes (`+0x15F`, 1–20 ↔ 5–100 internal scale), CA/PA, and positional ratings.
- **Fast Zstandard Indexing:** Decompresses `.fm` save streams indexing 46,500+ players and 988,000+ dictionary names in `<0.15s` for instant name-only lookup.

---

## Additional Desktop, Systems & Web Projects

| Repository | Stack | Highlights | Links |
| :--- | :--- | :--- | :---: |
| [`discord-wordle-destroyer`](https://github.com/lunizura/discord-wordle-destroyer) | C99 • Raylib 6.0 | 120 FPS frosted-glass Wordle solver using Shannon entropy & procedural C audio (`v1.0.1`) | [Release](https://github.com/lunizura/discord-wordle-destroyer/releases) |
| [`c-midterm-arena`](https://github.com/lunizura/c-midterm-arena) | C99 • HTML5/JS | Interactive CS101 C exam trap debugger (100 traps, visual memory stepper, CLI + Desktop + Web) | [Live Demo](https://lunizura.github.io/c-midterm-arena/) |
| [`minecraft-mod-menu`](https://github.com/lunizura/minecraft-mod-menu) | Python • NBT • CTk | Lossless binary NBT save editor, God-item forge & Hardcore reviver for Minecraft 26.x / 1.21 | [Release](https://github.com/lunizura/minecraft-mod-menu/releases) |
| [`stardew-mastermenu`](https://github.com/lunizura/stardew-mastermenu) | Python • XML/WGS | Stardew Valley 1.6+ save control suite supporting Steam, GOG & Xbox Game Pass `containers.index` | [Release](https://github.com/lunizura/stardew-mastermenu/releases) |
| [`gacha-builder-api-learninglabs`](https://github.com/lunizura/gacha-builder-api-learninglabs) | Flask • PostgreSQL | 14-table relational REST API on Vercel + Supabase with interactive SPA dashboard & 42 tests | [Live UI](https://gacha-builder-api-learninglabs.vercel.app/ui) |

---

## Technical Skills & Toolchain

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, C++20, C (C99), JavaScript, SQL, PowerShell |
| **Systems & Reverse Engineering** | Win32 API, Windows Internals, Process Memory Analysis, Binary Format RE, Ghidra SRE, x64dbg, Cheat Engine |
| **3D Graphics & Rendering** | glTF 2.0 Binary Compilation, Software Rasterization, Raylib, Unity Asset Extraction, Blender |
| **Engineering & Tooling** | CMake, GitHub Actions CI, Clang ASan/UBSan, Pytest/Unittest, Ruff, Flask, PostgreSQL, Git |

---

## Open Data & Civic Tools

Open educational datasets and interactive admissions explorers for Indonesian higher education (SNBP / SNBT / Mandiri):

| Repository | Scope | Live Explorer |
| :--- | :--- | :---: |
| [`keketatan-univ-indonesia`](https://github.com/lunizura/keketatan-univ-indonesia) | Top 50 PTN & PTS selectivity leaderboard & choice-portfolio risk simulator (ID / EN) | [Live Demo](https://lunizura.github.io/keketatan-univ-indonesia/) |
| [`ui-prodi-directory`](https://github.com/lunizura/ui-prodi-directory) | Universitas Indonesia study programs, quotas, and accreditation dataset | [Live Demo](https://lunizura.github.io/ui-prodi-directory/) |
| [`itb-prodi-directory`](https://github.com/lunizura/itb-prodi-directory) | Institut Teknologi Bandung TPB admission models & school accreditations | [Live Demo](https://lunizura.github.io/itb-prodi-directory/) |
| [`ugm-prodi-directory`](https://github.com/lunizura/ugm-prodi-directory) | Universitas Gadjah Mada academic directory, degree levels, and intake matrix | [Live Demo](https://lunizura.github.io/ugm-prodi-directory/) |
| [`uns-prodi-directory`](https://github.com/lunizura/uns-prodi-directory) | Universitas Sebelas Maret program accreditation & entrance capacity records | [Live Demo](https://lunizura.github.io/uns-prodi-directory/) |

---

<div align="center">
  <img src="assets/footer.svg?v=3" width="100%" alt="lunizura Crimson Horizons" />
</div>
