<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=&animation=fadeIn" width="100%"/>

<!-- Typing SVG -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=false&width=700&height=80&lines=Electronics+%26+Communication+Engineering" alt="Typing SVG" />
</a>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=18&duration=2000&pause=800&color=8B949E&center=true&vCenter=true&width=700&height=50&lines=RTL+Design+%7C+Computer+Architecture+%7C+RISC-V+%7C+ASIC+Design;GPU+Architecture+%7C+AI+Accelerators+%7C+Hardware+Verification" alt="Typing SVG" />
</a>

<br/>

<!-- Profile Views & Social Badges -->
![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)

</div>

---

<!-- About Me -->
## `> whoami`

```systemverilog
module student #(
    parameter DEGREE     = "B.Tech ECE",
    parameter FOCUS      = "Computer Architecture & RTL Design",
    parameter STATUS     = "Undergraduate"
) (
    input  wire  curiosity,
    input  wire  discipline,
    output reg   hardware_knowledge,
    output reg   rtl_implementations
);
```

```
 ┌─────────────────────────────────────────────────────────────┐
 │  ECE Student  ·  Hardware Enthusiast  ·  Architecture Nerd  │
 │                                                             │
 │  Learning by building: RTL design, CPU/GPU microarchitecture│
 │  exploration, and hardware verification — one module at a   │
 │  time. Interested in how compute is shaped at the silicon   │
 │  level, and why those decisions matter for AI workloads.    │
 └─────────────────────────────────────────────────────────────┘
```

- 🎓 &nbsp; Electronics & Communication Engineering undergraduate
- 🔬 &nbsp; Learning through hands-on RTL implementation and simulation
- 🧠 &nbsp; Exploring GPU microarchitecture and RISC-V processor design
- 📖 &nbsp; Working through Hennessy & Patterson, Harris & Harris
- 🛠️ &nbsp; Building things in SystemVerilog, Verilog, and Python

---

<!-- Current Focus -->
## `> current --focus`

<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║              CURRENT LEARNING ROADMAP                    ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║   [█████████░░░]  RTL Design & Verification              ║
║   [███████░░░░░]  RISC-V ISA & Processor Microarchitecture║
║   [██████░░░░░░]  GPU Architecture & Parallel Compute    ║
║   [████░░░░░░░░]  AI Accelerator Architecture            ║
║   [███░░░░░░░░░]  ASIC Physical Design Flow              ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

</div>

| Area | What I'm Exploring |
|------|-------------------|
| 🖥️ **RTL Design** | Writing synthesizable SystemVerilog, clean module hierarchies, design for testability |
| ⚙️ **Processor Architecture** | Pipelining, hazard handling, branch prediction, out-of-order concepts |
| 🎮 **GPU Architecture** | SIMT execution, warp scheduling, memory hierarchy (L1/L2/DRAM), SM design |
| 🤖 **AI Accelerators** | Systolic arrays, dataflow architectures, MAC units, weight/activation memory tradeoffs |
| 🔩 **ASIC Flow** | RTL → Synthesis → STA fundamentals using open-source EDA tools |
| ✅ **Verification** | UVM basics, constrained random testing, coverage-driven verification |

---

<!-- Technical Interests -->
## `> cat interests.md`

<div align="center">

```
 ┌────────────────┐    ┌─────────────────┐    ┌──────────────────┐
 │  MICROARCH     │    │   MEMORY SYS    │    │  COMPUTE FABRIC  │
 │                │    │                 │    │                  │
 │  • Pipelines   │    │  • Cache hier.  │    │  • SIMT/SIMD     │
 │  • OoO exec    │◄──►│  • Coherence    │◄──►│  • Warp sched.   │
 │  • Branch pred │    │  • TLB/MMU      │    │  • Interconnects │
 │  • Scoreboards │    │  • Prefetching  │    │  • Crossbars     │
 └────────────────┘    └─────────────────┘    └──────────────────┘
          │                    │                       │
          └────────────────────┼───────────────────────┘
                               │
                    ┌──────────▼──────────┐
                    │   RTL IMPLEMENTATION │
                    │                     │
                    │  SystemVerilog  ·  Verilog  │
                    │  Testbenches  ·  Simulation │
                    └─────────────────────┘
```

</div>

---

<!-- Featured Projects -->
## `> ls projects/`

<br/>

### 🔲 &nbsp; GridX³ — Experimental GPU Architecture

<img align="right" width="300" src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>

```
Architecture Sketch:

  ┌──────────────────────────────────────────┐
  │              GridX³ Core                 │
  │                                          │
  │  ┌──────────┐   ┌──────────┐            │
  │  │  SM / CU  │   │  SM / CU  │  · · ·  │
  │  │  ────────  │   │  ────────  │         │
  │  │ Warp Sched│   │ Warp Sched│         │
  │  │ ALU Array │   │ ALU Array │         │
  │  │ Reg File  │   │ Reg File  │         │
  │  └────┬─────┘   └────┬─────┘          │
  │       │               │                 │
  │  ─────┴───────────────┴──────────────  │
  │          Shared Memory Fabric           │
  │  ─────────────────────────────────────  │
  │        L2 Cache / Memory Controller     │
  └──────────────────────────────────────────┘
```

> Experimental exploration of scalable GPU compute fabrics. Studying how streaming multiprocessors organize execution, how shared memory and register files interact with parallel workloads, and what tradeoffs arise in memory system design for throughput-oriented architectures.

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF6B35?style=flat-square&logo=v&logoColor=white)
![Status](https://img.shields.io/badge/Status-In_Development-1f6feb?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Microarchitecture_Exploration-8b949e?style=flat-square)

---

### ⚡ &nbsp; Nexora SIMD — Parameterized SIMD Architecture

```
  Parameter: LANES = N

  ┌────────────────────────────────────────────────────────┐
  │                   Nexora SIMD Engine                   │
  │                                                        │
  │  Control Unit ──► Instruction Decode ──► Lane Dispatch │
  │                                              │         │
  │         ┌───────────────────────────────────┤         │
  │         │                                   │         │
  │  ┌──────▼───┐  ┌──────────┐  ┌──────────┐  │  · · · │
  │  │  Lane 0  │  │  Lane 1  │  │  Lane 2  │  │        │
  │  │ ───────  │  │ ───────  │  │ ───────  │  │        │
  │  │  ALU     │  │  ALU     │  │  ALU     │  │        │
  │  │  RF Slice│  │  RF Slice│  │  RF Slice│  │        │
  │  │  Mask Bit│  │  Mask Bit│  │  Mask Bit│  │        │
  │  └──────────┘  └──────────┘  └──────────┘  │        │
  │                                              │        │
  │              Lane Mask Register ◄───────────┘        │
  └────────────────────────────────────────────────────────┘
```

> Parameterized SIMD processor written in SystemVerilog. The design features configurable Processing Elements, per-lane ALUs, distributed register files, and lane masking for predicated execution. Accompanied by verification testbenches that validate functional correctness across parameter configurations.

**Key design decisions studied:**
- `parameter LANES` controls PE count without structural RTL changes
- Lane masking enables predicated compute at the hardware level
- Register file partitioning across lanes and its bandwidth implications
- Testbench architecture for parameterized DUT coverage

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF6B35?style=flat-square&logo=v&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-2ea043?style=flat-square)
![Verification](https://img.shields.io/badge/Verified-Simulation-6e40c9?style=flat-square)

---

### 🧩 &nbsp; RISC-V Learning Core — Educational CPU Implementation

```
  RV32I Base ISA — Pipelined Datapath

  ┌──────┐   ┌──────┐   ┌──────┐   ┌──────┐   ┌──────┐
  │  IF  │──►│  ID  │──►│  EX  │──►│  MEM │──►│  WB  │
  │      │   │      │   │      │   │      │   │      │
  │  PC  │   │  RF  │   │  ALU │   │  D$  │   │  RF  │
  │  I$  │   │ Imm  │   │  BRN │   │      │   │ Mux  │
  │      │   │ Ctrl │   │      │   │      │   │      │
  └──────┘   └──────┘   └──────┘   └──────┘   └──────┘
               │                       │
               │◄──── Hazard Unit ─────┘
               │      (Forwarding,
               │       Stall detect)
```

> An educational RISC-V RV32I processor implementation used as a vehicle for learning pipeline microarchitecture. The focus is on understanding instruction decode logic, datapath multiplexing, hazard detection and forwarding paths, and how control signals propagate through pipeline stages. RTL written with clarity over optimization.

**Concepts implemented and studied:**
- Instruction decode for R / I / S / B / U / J type encodings
- Data hazard detection and forwarding unit
- Control hazard handling (flush on branch)
- Separate instruction and data memory interfaces

![Verilog](https://img.shields.io/badge/Verilog-1a73e8?style=flat-square&logo=v&logoColor=white)
![RISCV](https://img.shields.io/badge/RISC--V-RV32I-FF6B35?style=flat-square)
![Status](https://img.shields.io/badge/Status-Learning_Build-8b949e?style=flat-square)

---

<!-- Research & Exploration -->
## `> cat research_log.txt`

```
[EXPLORING]  Memory wall problem and how modern architectures work around it
[STUDYING]   Systolic array design for matrix-multiply acceleration
[READING]    Cache coherence protocols (MESI, MOESI) and their RTL implications
[BUILDING]   Small verification environments to understand UVM structure
[LEARNING]   Static timing analysis concepts and constraint writing
[REVIEWING]  GPU shader core organization and warp-level execution semantics
[CURIOUS]    Near-memory compute and processing-in-memory architectures
[FOLLOWING]  Open-source ASIC toolchains (OpenROAD, OpenLane, Yosys)
```

---

<!-- Technical Stack -->
## `> lspci --tech-stack`

<div align="center">

**HDL & Design**

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF6B35?style=for-the-badge&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-1a73e8?style=for-the-badge&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-6e40c9?style=for-the-badge&logoColor=white)

**Simulation & Verification**

![ModelSim](https://img.shields.io/badge/ModelSim-00897B?style=for-the-badge&logoColor=white)
![Icarus Verilog](https://img.shields.io/badge/Icarus_Verilog-37474F?style=for-the-badge&logoColor=white)
![GTKWave](https://img.shields.io/badge/GTKWave-FF8F00?style=for-the-badge&logoColor=white)
![Verilator](https://img.shields.io/badge/Verilator-283593?style=for-the-badge&logoColor=white)

**Scripting & Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**EDA & Open-Source Flow**

![Yosys](https://img.shields.io/badge/Yosys-161b22?style=for-the-badge&logoColor=white)
![OpenLane](https://img.shields.io/badge/OpenLane-0d1117?style=for-the-badge&logoColor=orange)
![Vivado](https://img.shields.io/badge/Vivado-E91E63?style=for-the-badge&logoColor=white)

**ISA & Architecture Reference**

![RISCV](https://img.shields.io/badge/RISC--V-283593?style=for-the-badge&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_ISA-0091EA?style=for-the-badge&logo=arm&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA_Concepts-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

---

<!-- GitHub Analytics -->
## `> git log --stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=1f6feb&text_color=8b949e"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff6b35&currStreakLabel=58a6ff" alt="GitHub Streak"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=0d1117&color=58a6ff&line=1f6feb&point=ff6b35&area=true&hide_border=true" alt="Contribution Graph"/>

</div>

---

<!-- Currently Reading / Studying -->
## `> bookshelf --active`

```
 📘  Computer Organization and Design: RISC-V Edition  — Patterson & Hennessy
 📗  Digital Design and Computer Architecture          — Harris & Harris
 📙  Computer Architecture: A Quantitative Approach    — Hennessy & Patterson
 📕  SystemVerilog for Design                         — Sutherland et al.
 📓  The RISC-V Reader                               — Patterson & Waterman
 📄  GPU Architecture Papers (Volta, Turing, Ampere whitepapers)
```

---

<!-- Connect -->
## `> ping --connect`

<div align="center">

```
  Open to:
  ┌──────────────────────────────────────────────┐
  │  • Architecture discussions and paper reviews │
  │  • RTL review and feedback on my designs      │
  │  • Collaboration on open-source hardware      │
  │  • Learning from engineers in the field       │
  └──────────────────────────────────────────────┘
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_PROFILE)
&nbsp;
[![Email](https://img.shields.io/badge/Email-Reach_Out-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
&nbsp;
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/YOUR_HANDLE)

<br/>

*"The best way to understand architecture is to implement it."*

</div>

<!-- Footer Wave -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer" width="100%"/>
