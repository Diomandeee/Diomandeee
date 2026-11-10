# Mohamed Diomande

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
| [lume-enclosure](https://github.com/Diomandeee/lume-enclosure) | Parametric enclosure for a depth-camera stage unit. 18 printable parts, including joint coupons to test fit before the big prints. | OpenSCAD |
| [jeli-device](https://github.com/Diomandeee/jeli-device) | Printable N'Ko learning device: generated body STLs, an adjustable Raspberry Pi dock with geometry tests, and a browser device-twin. | Python, manifold3d |

### Cameras and motion

| Project | What it is | Built with |
| --- | --- | --- |
| [motionmix-core](https://github.com/Diomandeee/motionmix-core) | Core of a multi-camera capture hub: Record All as a transaction, a first-frame watchdog, receipts and pose signals. | Rust |
| [anticipation-geometry](https://github.com/Diomandeee/anticipation-geometry) | Seven numbers that describe where a trajectory is going, for motion, conversations or graphs. Evaluation results are in the repo. | Rust, Python |

### AI agent systems

| Project | What it is | Built with |
| --- | --- | --- |
| [meshd](https://github.com/Diomandeee/meshd) | Daemon that runs AI coding agents in terminal slots behind an HTTP API, across machines. | Rust |
| [pane-awareness](https://github.com/Diomandeee/pane-awareness) | Lets AI coding sessions in parallel terminals see each other's work, claim resources and hand off tasks. | Python |
| [trajectory-memory-ledger](https://github.com/Diomandeee/trajectory-memory-ledger) | Records coding-agent sessions, normalizes them to one schema and scores them for training. | Rust, Python |
| [karl](https://github.com/Diomandeee/karl) | Learns from recorded AI coding sessions: scores each one on six signals, exports the best as training data, and tests vector skill routing against regex rules. Based on the Trajectory Memory Ledger paper. | Python |

### Retrieval and training

| Project | What it is | Built with |
| --- | --- | --- |
| [rag-plusplus-core](https://github.com/Diomandeee/rag-plusplus-core) | Retrieval engine with SIMD vector search and an HNSW index. Published on crates.io. | Rust |
| [context-gateway](https://github.com/Diomandeee/context-gateway) | One retrieval endpoint over pgvector search, graph traversal and Gemini embeddings, with duplicate detection and echo suppression. | Python |
| [admissibility-kernel](https://github.com/Diomandeee/admissibility-kernel) | Deterministic context slicing for conversation graphs. Published on crates.io. | Rust |
| [live-knowledge-graphs](https://github.com/Diomandeee/live-knowledge-graphs) | Knowledge graph that AI agents read and update while they run, built around a deterministic context slicer. Evaluation results are in the repo. | Rust, Python |
| [thunder-train](https://github.com/Diomandeee/thunder-train) | Distributed LoRA fine-tuning across two Apple Silicon Macs over Thunderbolt. | Python, MLX |

### Developer tools

| Project | What it is | Built with |
| --- | --- | --- |
| [spatial-git](https://github.com/Diomandeee/spatial-git) | Walk through a repo's git history in 3D, and play the commits back as synthesized music. | JavaScript, Web Audio |

