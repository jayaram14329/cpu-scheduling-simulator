# CPU Scheduling Simulator // Mission Control

A professional, developer-tool-grade, single-file CPU scheduling simulator and operating system educational workbench.

**Live 24/7 Deployment:** [https://jayaram14329.github.io/cpu-scheduling-simulator/](https://jayaram14329.github.io/cpu-scheduling-simulator/)

---

## Highlights

- **Pure Offline Architecture**: 100% self-contained single `index.html` file. Zero external dependencies, no CDNs, no web fonts, works completely offline.
- **Hardware-Accelerated 3D Visuals**:
  - **CSS 3D Silicon CPU Die**: Multi-layer isometric silicon die with active core illumination, rotating vector circuit ring, and interactive mouse parallax tilt.
  - **3D Ready Queue**: Process cards layered in depth along the Z-axis with burst progress fill, slide-in dispatch, and preemption/demotion animations.
  - **3D Extruded Gantt Chart**: Isometric floor grid with 3D extruded process blocks (height proportional to burst time), scrubber playhead, and a toggle for a crisp 2D flat mode. Clicking any block scrubs directly to that tick.
  - **MLFQ Priority Lanes**: 3 distinct visual tiers (Q0 $q=2$, Q1 $q=4$, Q2 FCFS) with dynamic demotion animations and aging boost promotions.
  - **Canvas 2D Data Flow**: Subtle photon packet flow between the ready queue and CPU die that scales dynamically with simulation speed.
  - **Real-Time Heuristics**: Rolling CPU utilization sparkline and dynamic algorithm benchmark bar race comparing Average Waiting Time.
- **5 Scheduling Algorithms**:
  1. **FCFS** (First-Come, First-Served - Non-preemptive)
  2. **SJF** (Shortest Job First - Non-preemptive)
  3. **SRTF** (Shortest Remaining Time First - Preemptive)
  4. **RR** (Round Robin - Configurable time quantum)
  5. **MLFQ** (Multi-Level Feedback Queue with 3 tiers and starvation-preventing aging boost)
- **Presets**: Standard Mix, Convoy Effect, MLFQ Demotion, Random Load.
- **Full Playback Controls**: Play, pause, step forward, step backward, scrubber slider, speed control (0.25x - 4x), keyboard shortcuts.
- **Developer Dock**:
  - **Metrics Table**: CT, TAT ($CT - AT$), WT ($TAT - BT$), RT, completion highlight, formula tooltips, and summary averages.
  - **Operation Log**: Plain English event traces with tick stamps, filterable by event type, search filter, and clipboard copy.
  - **Lab Report & C Reference Code**: Contextual experiment aim, formal pseudocode, syntax-highlighted standalone C reference code with one-click copy, live experiment run output matching simulation, and OS viva FAQ accordions.
  - **Exports**: Download Gantt chart as standalone SVG, and Metrics as CSV.
- **Command Palette (`Ctrl+K` / `Cmd+K`)**: Rapid keyboard-driven navigation to switch algorithms, presets, controls, themes, and views.
- **Accessibility & Themes**:
  - High-contrast Dark (graphite/slate) and Light (cool paper-grey) themes.
  - Strict compliance with `prefers-reduced-motion` and `prefers-color-scheme`.
  - Responsive down to 400px.

---

## Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl+K` / `Cmd+K` | Open Command Palette |
| `Space` | Play / Pause Simulation |
| `Right Arrow` | Step Forward by 1 Tick |
| `Left Arrow` | Step Backward by 1 Tick |
| `R` | Reset Simulation to Tick 0 |
| `F` | Fast-Forward to Completion |
| `Esc` | Close Modal / Command Palette |

---

## License

MIT License. Designed and built for operating system education and developer exploration.
