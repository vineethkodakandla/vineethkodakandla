## Vineeth Reddy Kodakandla

**ML engineer: inference and perception on real hardware.** I make trained models fast and reliable in production, and when I publish a number, the harness that produced it is in the same repository.

Currently an ML engineering intern at Caterpillar, optimizing perception models for NVIDIA Jetson and DRIVE Orin. Before my M.S. in Computer Science: LLM inference serving at EXL and real-time medical vision at L&T Technology Services.

[Portfolio](https://vineeth-portfolio-five.vercel.app) · [LinkedIn](https://linkedin.com/in/vineethkodakandla) · vineethkodakandla@gmail.com

---

### Selected work

| Project | What it does | Live |
|---|---|---|
| **[edge-vision-lab](https://github.com/vineethkodakandla/edge-vision-lab)** | Meteor Lake Latency Lab. YOLOv8n-seg INT8 through OpenVINO on the NPU, Arc iGPU and CPU of an Intel Core Ultra 7 155H, against a 33.3 ms frame budget. Run back to back, the NPU holds the tail (18.0 ms p99) while the iGPU degrades to 47 ms; on a live webcam feed the ranking flips (iGPU 13.3 ms, NPU 22.3 ms p99). | [report](https://vineethkodakandla.github.io/edge-vision-lab/) |
| **[bitwise-forensics](https://github.com/vineethkodakandla/bitwise-forensics)** | Asks whether an LLM serving engine returns the same tokens when requests share engine steps. 2 devices × 12 configurations × 40 prompts × 8 trials on OpenVINO GenAI, with bootstrap intervals on every rate. | [results](https://github.com/vineethkodakandla/bitwise-forensics/tree/main/results/openvino) |
| **[llm-eval-observatory](https://github.com/vineethkodakandla/llm-eval-observatory)** | Evaluates open-weight models nightly: capability drift, prompt-injection robustness and LLM-as-judge agreement. GitHub Actions runs it, Vercel shows it, and the dashboard is the artifact, not a screenshot of one. | [dashboard](https://llm-eval-observatory.vercel.app) |
| **[edith-lab](https://github.com/vineethkodakandla/edith-lab)** | A multi-agent orchestrator (Researcher, Analyst, Critic, Synthesizer) with a Reflexion loop and a Governor policy gate. Framework-free. | [demo](https://vineethkodakandla.github.io/edith-lab/) |
| **[ananta-lab](https://github.com/vineethkodakandla/ananta-lab)** | A governed memory-augmented agent: Ebbinghaus-decay episodic memory, a SHA-256 tamper-evident audit chain, confidence-banded model routing and a Reflexion RAG loop. Zero dependencies. | [demo](https://vineethkodakandla.github.io/ananta-lab/) |
| **[pathwise-ai](https://github.com/vineethkodakandla/pathwise-ai)** | Team project. SD-WAN management platform: LSTM link-degradation forecasting, autonomous traffic steering, a digital-twin sandbox and intent-based networking, behind a multi-tenant React dashboard. | [demo](https://pathwise-ai-swart.vercel.app) |

---

### Tools

**Edge inference** TensorRT, ONNX Runtime, OpenVINO, INT8/FP16 quantization, NVIDIA Jetson, CUDA
**LLM serving** OpenVINO GenAI, continuous batching, KV-cache quantization, Triton, TensorRT-LLM
**ML** PyTorch, YOLOv8, RT-DETR, LSTM/sequence forecasting, scikit-learn, bootstrap & interval estimation
**LLM systems** RAG (hybrid dense + BM25, RRF), pgvector, ChromaDB, LLM-as-judge, prompt-injection testing
**Backend** Python, C++, FastAPI, Postgres, Docker
**Frontend** TypeScript, Next.js, React, three.js
**Infra** GitHub Actions, Vercel, scheduled evaluation pipelines

---

*Every project above links to a live deployment or to committed results. If a number appears in a README of mine, the code that produced it is in the same repository.*
