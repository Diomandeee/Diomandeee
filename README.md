# Mohamed Diomande

I build software and hardware: iOS apps, multi-camera systems, machine learning models, tools for AI coding agents, and parts designed in CAD for 3D printing. Most of it starts from a problem I've seen up close, and I keep working on it until it holds up in real use.

[Portfolio](https://granddiomande.com) · [LinkedIn](https://linkedin.com/in/diomandee)

## Skills

- **Languages:** Swift, Rust, Python, TypeScript, C#
- **Apps and backend:** SwiftUI, iOS, REST APIs, Postgres, Supabase, Cloudflare Workers
- **Machine learning:** PyTorch, MLX, computer vision, pose estimation, OCR, speech recognition, LoRA fine-tuning
- **Hardware:** OpenSCAD, Blender, 3D printing, Raspberry Pi, depth cameras, sensor integration
- **Agent systems:** multi-agent orchestration, retrieval, code review gates, AI coding agents

## Public projects

### Hardware

| Project | What it is | Built with |
| --- | --- | --- |
| [lume-enclosure](https://github.com/Diomandeee/lume-enclosure) | Parametric enclosure for a depth-camera stage unit. 18 printable parts, with joint coupons to test fit before the big prints. | OpenSCAD |
| [jeli-device](https://github.com/Diomandeee/jeli-device) | Printable N'Ko learning device: generated body STLs, an adjustable Raspberry Pi dock with geometry tests, and a browser device-twin. | Python, manifold3d |

### Cameras and motion

| Project | What it is | Built with |
| --- | --- | --- |
| [motionmix-core](https://github.com/Diomandeee/motionmix-core) | Core of a multi-camera capture hub: Record All as a transaction, a first-frame watchdog, receipts and pose signals. 88 tests. | Rust |
| [anticipation-geometry](https://github.com/Diomandeee/anticipation-geometry) | Seven numbers that describe where a trajectory is going, for motion, conversations or graphs. Evaluation results are in the repo. | Rust, Python |

### AI agent systems

| Project | What it is | Built with |
| --- | --- | --- |
| [foundry](https://github.com/Diomandeee/foundry) | Merge gate for teams of AI agents. Agents push to their own forks, a deterministic checker approves or refuses each change, and every decision is recorded with its reason. | TypeScript, Cloudflare Workers |
| [meshd](https://github.com/Diomandeee/meshd) | Daemon that runs AI coding agents in terminal slots behind an HTTP API, across machines. | Rust |
| [pane-awareness](https://github.com/Diomandeee/pane-awareness) | Lets AI coding sessions in parallel terminals see each other's work, claim resources and hand off tasks. | Python |
| [trajectory-memory-ledger](https://github.com/Diomandeee/trajectory-memory-ledger) | Records coding-agent sessions, normalizes them to one schema and scores them for training. | Rust, Python |

### Retrieval and training

| Project | What it is | Built with |
| --- | --- | --- |
| [rag-plusplus-core](https://github.com/Diomandeee/rag-plusplus-core) | Retrieval engine with SIMD vector search and an HNSW index. Published on crates.io. | Rust |
| [admissibility-kernel](https://github.com/Diomandeee/admissibility-kernel) | Deterministic context slicing for conversation graphs. Published on crates.io. | Rust |
| [thunder-train](https://github.com/Diomandeee/thunder-train) | Distributed LoRA fine-tuning across two Apple Silicon Macs over Thunderbolt. | Python, MLX |

## Private work

Some of my work stays private because it holds details of my own setup or unreleased data:

- **Fabric:** how I run AI coding agents across several machines and approve their work from my phone.
- **MotionMix:** iPhone apps that track body pose and the full hub that picks the best camera live.
- **LUME:** live stage visuals driven by a depth camera, in Python and Unity.
- **Air Deck:** software that works with a real DJ controller over USB.
- **Jeli models:** N'Ko OCR, speech and tone models.

The portfolio has drawings, photos and results.
