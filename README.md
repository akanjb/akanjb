<!-- ============================================================
     Profile README — akanjb
     Sections: Header · About · AI & LLM Engineering · Tech Stack ·
               Fundamentals · Security · Featured Work · Live Projects · Analytics
     ============================================================ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b27,100:7aa2f7&height=220&section=header&text=Nikunj%20Bansal&fontSize=64&fontColor=c0caf5&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20LLM%20Builder%20%C2%B7%20Systems%20Developer&descAlignY=58&descSize=20" width="100%" alt="Nikunj Bansal" />

<a href="https://github.com/akanjb">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=7AA2F7&center=true&vCenter=true&width=760&lines=I+build+Large+Language+Models+from+scratch;I+design+autonomous+AI+agents+and+agent+skills;Rust+%C2%B7+Python+%C2%B7+TypeScript+%C2%B7+Kotlin+%C2%B7+Java;Docker+%C2%B7+Kubernetes+%C2%B7+Cloud-native+systems;Neural+networks%2C+RAG%2C+fine-tuning%2C+inference;Local-first.+Privacy-first.+Production-grade." alt="Typing animation" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=akanjb&style=for-the-badge&color=7aa2f7&labelColor=1a1b27&label=PROFILE+VIEWS" alt="Profile views" />
<img src="https://img.shields.io/github/followers/akanjb?style=for-the-badge&logo=github&logoColor=c0caf5&labelColor=1a1b27&color=bb9af7" alt="Followers" />
<img src="https://img.shields.io/badge/Focus-AI%20%26%20LLM%20Systems-9ece6a?style=for-the-badge&labelColor=1a1b27" alt="Focus" />

</div>

---

## 🧠 About Me

```python
class NikunjBansal:
    """Engineer who turns research papers into shipped software."""

    role       = "AI Engineer · LLM Builder · Full-Stack & Systems Developer"
    builds     = ["LLMs from scratch", "AI agents", "agent skills", "MCP servers",
                  "RAG pipelines", "desktop apps", "browser extensions"]
    languages  = ["Python", "Rust", "TypeScript", "JavaScript", "Kotlin", "Java",
                  "Go", "C", "C++", "SQL", "HTML", "CSS", "Bash"]
    infra      = ["Docker", "Kubernetes", "Terraform", "AWS", "GCP", "Azure", "CI/CD"]
    principles = ["local-first", "privacy-first", "measure before optimizing",
                  "clean architecture", "ship it"]

    def currently(self) -> str:
        return "Building VEYRA — an AI usage intelligence monitor in Rust + Tauri"
```

---

## 🤖 AI & LLM Engineering

> From tokenizer to deployed agent — the full lifecycle of a modern language model.

<details open>
<summary><b>🏗️ Building LLMs from Scratch</b></summary>
<br/>

| Stage | What I work with |
|:--|:--|
| **Data** | Web-scale corpus curation, deduplication (MinHash / LSH), quality filtering, PII scrubbing, data mixtures, synthetic data generation |
| **Tokenization** | BPE, WordPiece, Unigram, SentencePiece, tiktoken, byte-level tokenizers, vocabulary design |
| **Architecture** | Transformers, multi-head / multi-query / grouped-query attention, RoPE & ALiBi, RMSNorm, SwiGLU, Mixture-of-Experts, state-space models (Mamba) |
| **Pre-training** | Next-token prediction, scaling laws (Chinchilla), mixed precision (BF16 / FP8), gradient checkpointing, learning-rate schedules, curriculum learning |
| **Distributed Training** | Data / tensor / pipeline / sequence parallelism, FSDP, DeepSpeed ZeRO, Megatron-LM, NCCL, multi-node GPU clusters |
| **Post-training** | Supervised fine-tuning, instruction tuning, RLHF (PPO), DPO, ORPO, KTO, GRPO, RLAIF, constitutional methods, reward modelling |
| **Efficient Fine-tuning** | LoRA, QLoRA, DoRA, adapters, prefix tuning, PEFT, Unsloth, Axolotl |
| **Inference & Serving** | KV cache, PagedAttention, FlashAttention, continuous batching, speculative decoding, vLLM, TGI, TensorRT-LLM, SGLang, llama.cpp, Ollama |
| **Compression** | Quantization (GPTQ, AWQ, GGUF, bitsandbytes, INT8 / INT4), pruning, knowledge distillation |
| **Evaluation** | Perplexity, MMLU, HumanEval, GSM8K, SWE-bench, LLM-as-a-judge, custom eval harnesses, regression evals |
| **Safety & Alignment** | Red-teaming, guardrails, jailbreak defence, prompt-injection mitigation, interpretability, hallucination detection |

</details>

<details open>
<summary><b>🕹️ AI Agents, Skills & Tooling</b></summary>
<br/>

| Area | What I work with |
|:--|:--|
| **Agent Design** | Tool use & function calling, ReAct, plan-and-execute, reflection, self-critique, long-horizon task decomposition |
| **Multi-Agent Systems** | Orchestrator-worker patterns, sub-agents, agent handoffs, A2A protocol, shared memory, consensus & voting |
| **Agent Frameworks** | LangGraph, LangChain, LlamaIndex, CrewAI, AutoGen, Semantic Kernel, DSPy, OpenAI Agents SDK, Claude Agent SDK, Google ADK |
| **Protocols** | Model Context Protocol (MCP) servers & clients, tool schemas, structured outputs, JSON mode |
| **Skill Creation** | Authoring reusable agent skills, slash commands, hooks, sub-agent definitions, skill evals and trigger optimization |
| **Context Engineering** | Prompt engineering, system prompts, few-shot design, context-window management, prompt caching, compaction |
| **Memory** | Short-term scratchpads, episodic & semantic memory, vector memory, knowledge graphs |
| **Agent Ops** | Tracing & observability (LangSmith, Langfuse, OpenTelemetry), cost & token tracking, sandboxing, human-in-the-loop |
| **AI Coding Agents** | Claude Code, Codex CLI, Gemini CLI, Copilot, Cursor, OpenCode — and the telemetry behind them |

</details>

<details>
<summary><b>🔎 Retrieval-Augmented Generation</b></summary>
<br/>

| Area | What I work with |
|:--|:--|
| **Embeddings** | Sentence transformers, OpenAI / Voyage / Cohere embeddings, Matryoshka embeddings, fine-tuned bi-encoders |
| **Vector Stores** | pgvector, Pinecone, Weaviate, Qdrant, Milvus, Chroma, FAISS |
| **Retrieval** | Hybrid search (BM25 + dense), re-ranking (cross-encoders, ColBERT), query rewriting, HyDE, multi-hop retrieval |
| **Pipelines** | Chunking strategies, document parsing, metadata filtering, GraphRAG, agentic RAG, citation grounding |

</details>

<details>
<summary><b>🧬 Deep Learning & Neural Networks</b></summary>
<br/>

| Area | What I work with |
|:--|:--|
| **Foundations** | Linear algebra, calculus, probability, optimization, backpropagation, automatic differentiation |
| **Architectures** | MLPs, CNNs, RNNs, LSTMs, GRUs, Transformers, ResNets, U-Nets, GNNs, autoencoders, VAEs, GANs |
| **Generative Models** | Diffusion models, latent diffusion, flow matching, autoregressive image & audio models |
| **Multimodal** | Vision Transformers, CLIP, vision-language models, Whisper / speech, text-to-speech |
| **Classical ML** | Regression, SVMs, decision trees, random forests, XGBoost, LightGBM, clustering, PCA, feature engineering |
| **Reinforcement Learning** | MDPs, Q-learning, DQN, policy gradients, PPO, actor-critic |
| **Frameworks** | PyTorch, JAX, TensorFlow, Keras, Hugging Face Transformers, scikit-learn, NumPy, pandas |
| **MLOps** | MLflow, Weights & Biases, DVC, Ray, Kubeflow, model registries, feature stores, ONNX, Triton |

</details>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/JAX-A8B9CC?style=for-the-badge&logo=google&logoColor=black" alt="JAX" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openaigym&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" alt="MLflow" />
  <img src="https://img.shields.io/badge/W%26B-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black" alt="Weights & Biases" />
</p>

---

## 🛠️ Tech Stack

<table align="center">
  <tr>
    <td align="center" width="170"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,rust,ts,js,kotlin,java,go,c,cpp,cs,dart,swift,php,ruby,scala,haskell,r,lua,solidity,bash,powershell&perline=11&theme=dark" alt="Languages" /></td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=html,css,react,nextjs,vue,svelte,angular,tailwind,sass,threejs,vite,webpack&perline=11&theme=dark" alt="Frontend" /></td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,bun,deno,express,nestjs,fastapi,django,flask,spring,graphql,kafka,rabbitmq&perline=11&theme=dark" alt="Backend" /></td>
  </tr>
  <tr>
    <td align="center"><b>Desktop & Mobile</b></td>
    <td><img src="https://skillicons.dev/icons?i=tauri,electron,androidstudio,flutter,wasm&perline=11&theme=dark" alt="Desktop and Mobile" /></td>
  </tr>
  <tr>
    <td align="center"><b>AI / ML</b></td>
    <td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&perline=11&theme=dark" alt="AI and ML" /></td>
  </tr>
  <tr>
    <td align="center"><b>DevOps & Cloud</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,ansible,aws,gcp,azure,cloudflare,vercel,nginx,githubactions,jenkins,prometheus,grafana&perline=11&theme=dark" alt="DevOps and Cloud" /></td>
  </tr>
  <tr>
    <td align="center"><b>Databases</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,mongodb,redis,supabase,firebase,prisma&perline=11&theme=dark" alt="Databases" /></td>
  </tr>
  <tr>
    <td align="center"><b>Tools & OS</b></td>
    <td><img src="https://skillicons.dev/icons?i=git,github,vscode,vim,postman,figma,linux,ubuntu,arch,windows,jest,vitest&perline=11&theme=dark" alt="Tools and OS" /></td>
  </tr>
</table>

<details>
<summary><b>☸️ Docker & Kubernetes in depth</b></summary>
<br/>

| Area | What I work with |
|:--|:--|
| **Containers** | Dockerfiles, multi-stage builds, BuildKit, Docker Compose, distroless & minimal images, image scanning, registries |
| **Kubernetes** | Pods, Deployments, StatefulSets, DaemonSets, Jobs, Services, Ingress, ConfigMaps, Secrets, RBAC, HPA / VPA |
| **Ecosystem** | Helm, Kustomize, Argo CD, Flux, Istio, Linkerd, cert-manager, KEDA, Karpenter, operators & CRDs |
| **Platforms** | EKS, GKE, AKS, k3s, kind, minikube, GPU node pools for model training & serving |
| **Observability** | Prometheus, Grafana, Loki, Jaeger, OpenTelemetry, alerting & SLOs |
| **IaC & Delivery** | Terraform, Pulumi, Ansible, GitHub Actions, GitLab CI, Jenkins, GitOps workflows |

</details>

---

## 📐 Engineering Fundamentals

<details>
<summary><b>Computer science & software craftsmanship</b></summary>
<br/>

| Area | Topics |
|:--|:--|
| **Data Structures & Algorithms** | Arrays, linked lists, stacks, queues, trees, heaps, tries, graphs, hashing, DP, greedy, backtracking, complexity analysis |
| **Operating Systems** | Processes & threads, scheduling, memory management, virtual memory, file systems, concurrency, synchronization |
| **Computer Networks** | OSI & TCP/IP, HTTP/1.1–3, TLS, DNS, WebSockets, gRPC, REST, load balancing, CDNs |
| **Databases** | Relational modelling, normalization, indexing, transactions & ACID, isolation levels, query planning, NoSQL trade-offs |
| **System Design** | Scalability, caching, sharding, replication, queues, rate limiting, CAP theorem, consistency models, microservices |
| **Distributed Systems** | Consensus (Raft, Paxos), event sourcing, CQRS, idempotency, back-pressure, observability |
| **Software Design** | OOP, functional programming, SOLID, DRY, design patterns, clean architecture, domain-driven design |
| **Quality** | Unit, integration & E2E testing, TDD, property-based testing, code review, static analysis, CI/CD |
| **Low-level** | Memory safety, ownership & borrowing, compilers & interpreters, concurrency primitives, performance profiling |

</details>

---

## 🔐 Security & Ethical Hacking

<details>
<summary><b>Offensive & defensive security basics</b></summary>
<br/>

| Area | Topics |
|:--|:--|
| **Web Security** | OWASP Top 10, XSS, CSRF, SQL injection, SSRF, IDOR, auth & session flaws, CSP, secure headers |
| **Network & Recon** | Nmap, Wireshark, packet analysis, enumeration, port scanning, traffic inspection |
| **Tooling** | Kali Linux, Burp Suite, Metasploit, Hydra, John the Ripper, Gobuster, sqlmap |
| **AI Security** | Prompt injection, jailbreaks, data exfiltration via tools, model supply-chain risks, LLM red-teaming |
| **Practice** | CTF challenges, reverse-engineering basics, cryptography fundamentals, secure-by-design development |

</details>

<p align="center">
  <img src="https://img.shields.io/badge/Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white" alt="Kali Linux" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white" alt="Metasploit" />
  <img src="https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP" />
</p>

---

## 🚀 Featured Work

<div align="center">

<a href="https://github.com/akanjb/VEYRA">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=akanjb&repo=VEYRA&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&icon_color=bb9af7&description_lines_count=3" alt="VEYRA" />
</a>

</div>

### [VEYRA](https://github.com/akanjb/VEYRA) — AI Usage Intelligence Monitor

A **local-first, privacy-first desktop dashboard** that unifies AI usage across model providers, coding agents, IDEs and CLIs into one accurate view.

- 📊 Tracks **tokens, API-equivalent cost, cache savings, sessions, models and projects**
- 🔌 Connectors for **Claude Code, Codex, Gemini CLI, OpenCode and Copilot CLI**, plus an opt-in local OpenTelemetry receiver and capture proxy
- 🧮 Verified pricing engine where **every number is marked exact or estimated**
- 🔒 **No telemetry, no accounts** — prompts are never stored; everything stays on your machine
- 🧱 Built with **Tauri 2 · Rust · React 19 · SQLite**, with generated contracts, accessibility checks and CI

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
</p>

> 🔒 **Plus 20+ private projects** — cross-browser extensions, a Tauri desktop app, fintech & equity-research tools, and productivity software.

---

## 🌐 Live Projects

<div align="center">

> Shipped, deployed and one click away — tap a button to open the real thing.

<img src="https://img.shields.io/badge/%E2%97%8F%20LIVE-9ece6a?style=flat-square" alt="Live" />
<img src="https://img.shields.io/badge/%E2%97%8F%20NOT%20PUBLICLY%20DEPLOYED-565f89?style=flat-square" alt="Not publicly deployed" />

<br/><br/>

<!-- ───── Flagship app ───── -->
<table width="100%">
  <tr>
    <td align="center" valign="middle" width="190" bgcolor="#1a1b27">
      <a href="https://finevergreen.netlify.app/"><img src="assets/icons/finevergreen.png" width="112" alt="FinEvergreen" /></a>
    </td>
    <td align="left" valign="middle" bgcolor="#1a1b27">
      <img src="https://img.shields.io/badge/%E2%97%8F%20LIVE-9ece6a?style=flat-square" alt="Live" />
      <img src="https://img.shields.io/badge/Personal%20Finance-bb9af7?style=flat-square" alt="Personal Finance" />
      <img src="https://img.shields.io/badge/Free%20%C2%B7%20Pro%20%C2%B7%20Max-7aa2f7?style=flat-square" alt="Free, Pro and Max plans" />
      <h3><a href="https://finevergreen.netlify.app/">FinEvergreen</a> — Ultimate Personal Finance App</h3>
      A secure, premium personal-finance app to track <b>income, expenses and transfers across multiple currencies</b>. It brings <b>budgets, goals, debt payoff, EMIs and planned payments</b> together with <b>smart insights, forecasts, a financial health score and 31 calculators</b> — plus Excel/CSV exports, reminders and App Lock. Runs on any device, and is built to run entirely on free services: <b>no paid APIs, no paid infrastructure</b>.
      <br/><br/>
      <a href="https://finevergreen.netlify.app/"><img src="assets/buttons/live-demo.svg" width="220" alt="Launch FinEvergreen" /></a>
    </td>
  </tr>
</table>

<br/>

### 🧩 Browser Extensions &nbsp;·&nbsp; Chrome & Edge

<table width="100%">
  <!-- logos -->
  <tr>
    <td align="center" width="33%" bgcolor="#1a1b27">
      <br/><a href="https://chromewebstore.google.com/detail/flowt-distraction-blocker/gblmoccpmpbiclnbkdciglogchofmocj"><img src="assets/icons/flowt.png" width="88" alt="Flowt" /></a>
    </td>
    <td align="center" width="33%" bgcolor="#1a1b27">
      <br/><a href="https://chromewebstore.google.com/detail/screener-smart-research/egbpfmckeohieknjdpaojnblbpconcff"><img src="assets/icons/screener.png" width="88" alt="Screener Smart Research" /></a>
    </td>
    <td align="center" width="33%" bgcolor="#1a1b27">
      <br/><a href="https://chromewebstore.google.com/detail/paceline-%E2%80%94-video-speed-co/igjjphgdnojmjalgpklbdhpmhljfaglo"><img src="assets/icons/paceline.png" width="88" alt="Paceline" /></a>
    </td>
  </tr>
  <!-- names -->
  <tr>
    <td align="center" bgcolor="#1a1b27"><b>Flowt</b><br/><sub>YouTube distraction blocker</sub></td>
    <td align="center" bgcolor="#1a1b27"><b>Screener Smart Research</b><br/><sub>Analyst-grade research on Screener.in</sub></td>
    <td align="center" bgcolor="#1a1b27"><b>Paceline</b><br/><sub>Video speed controller</sub></td>
  </tr>
  <!-- descriptions -->
  <tr>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>Blocks Shorts, the home feed, suggestions and autoplay — with focus timers, daily limits and schedules.</sub></td>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>Ratios, forensic scores, DuPont, ROIIC, reverse DCF and peer comparison. Free, runs locally.</sub></td>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>Set the speed of any HTML5 video — YouTube, Netflix, Prime Video and more — from 0.25× to 2.5×.</sub></td>
  </tr>
  <!-- Chrome buttons -->
  <tr>
    <td align="center" bgcolor="#1a1b27"><a href="https://chromewebstore.google.com/detail/flowt-distraction-blocker/gblmoccpmpbiclnbkdciglogchofmocj"><img src="assets/buttons/chrome.svg" width="172" alt="Add Flowt to Chrome" /></a></td>
    <td align="center" bgcolor="#1a1b27"><a href="https://chromewebstore.google.com/detail/screener-smart-research/egbpfmckeohieknjdpaojnblbpconcff"><img src="assets/buttons/chrome.svg" width="172" alt="Add Screener Smart Research to Chrome" /></a></td>
    <td align="center" bgcolor="#1a1b27"><a href="https://chromewebstore.google.com/detail/paceline-%E2%80%94-video-speed-co/igjjphgdnojmjalgpklbdhpmhljfaglo"><img src="assets/buttons/chrome.svg" width="172" alt="Add Paceline to Chrome" /></a></td>
  </tr>
  <!-- Edge buttons -->
  <tr>
    <td align="center" bgcolor="#1a1b27"><a href="https://microsoftedge.microsoft.com/addons/detail/flowt-distraction-block/icmenkknlhmognjdckaicocebbdedgik"><img src="assets/buttons/edge.svg" width="172" alt="Add Flowt to Edge" /></a></td>
    <td align="center" bgcolor="#1a1b27"><a href="https://microsoftedge.microsoft.com/addons/detail/screener-smart-research/ioignhkdficolihednbemdblahhgioai"><img src="assets/buttons/edge.svg" width="172" alt="Add Screener Smart Research to Edge" /></a></td>
    <td align="center" bgcolor="#1a1b27"><a href="https://microsoftedge.microsoft.com/addons/detail/paceline-%E2%80%94-video-speed-co/beknokklkkdlkmmffbjecodpkpfnflib"><img src="assets/buttons/edge.svg" width="172" alt="Add Paceline to Edge" /></a></td>
  </tr>
  <tr><td colspan="3" bgcolor="#1a1b27"></td></tr>
</table>

<br/>

### 📱 More Apps

<!-- TODO: add live-demo / store buttons here once public links for these three apps are available -->
<table width="100%">
  <tr>
    <td align="center" valign="top" width="33%" bgcolor="#1a1b27"><br/>⏱️<br/><b>Ultimate Productivity Tracker</b></td>
    <td align="center" valign="top" width="33%" bgcolor="#1a1b27"><br/>💸<br/><b>Income & Expense Tracker</b></td>
    <td align="center" valign="top" width="33%" bgcolor="#1a1b27"><br/>📊<br/><b>Trading Risk & Money Management Calculator</b></td>
  </tr>
  <tr>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>A modern productivity app built on proven principles and techniques to fight procrastination, sharpen focus and maximise efficiency.</sub></td>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>A dedicated mobile app for tracking and managing personal finances — income, spending and where the money goes.</sub></td>
    <td align="center" valign="top" bgcolor="#1a1b27"><sub>A professional-grade calculator for traders and scalpers — risk, position sizing and money management in one place.</sub></td>
  </tr>
  <tr>
    <td align="center" valign="top" bgcolor="#1a1b27">
      <img src="https://img.shields.io/badge/Productivity-9ece6a?style=flat-square" alt="Productivity" />
    </td>
    <td align="center" valign="top" bgcolor="#1a1b27">
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
      <br/>
      <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=1a1b27" alt="Android" />
      <img src="https://img.shields.io/badge/iOS-1a1b27?style=flat-square&logo=apple&logoColor=c0caf5" alt="iOS" />
      <img src="https://img.shields.io/badge/BCA%20Project-e0af68?style=flat-square" alt="BCA academic project" />
    </td>
    <td align="center" valign="top" bgcolor="#1a1b27">
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
      <br/>
      <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=1a1b27" alt="Android" />
      <img src="https://img.shields.io/badge/iOS-1a1b27?style=flat-square&logo=apple&logoColor=c0caf5" alt="iOS" />
      <img src="https://img.shields.io/badge/BCA%20Project-e0af68?style=flat-square" alt="BCA academic project" />
    </td>
  </tr>
</table>

<br/>

### 🔒 Not Publicly Deployed (Yet)

<table width="100%">
  <tr>
    <td align="center" bgcolor="#1a1b27">
      <img src="https://img.shields.io/badge/%E2%97%8F%20PRIVATE%20%2F%20IN%20DEVELOPMENT-565f89?style=flat-square" alt="Private or in development" />
      <br/><br/>
      🖥️ <b>Desktop application</b> for <b>macOS & Linux</b> &nbsp;·&nbsp; 🧩 <b>More browser extensions</b> &nbsp;·&nbsp; 🧪 <b>Other projects</b> still being built and polished before release.
    </td>
  </tr>
</table>

</div>

---

## 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=akanjb&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&icon_color=bb9af7&count_private=true&include_all_commits=true&rank_icon=github" height="170" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akanjb&layout=compact&theme=tokyonight&hide_border=true&bg_color=1a1b27&title_color=7aa2f7&langs_count=8" height="170" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=akanjb&theme=tokyonight&hide_border=true&background=1a1b27&ring=7aa2f7&fire=bb9af7&currStreakLabel=7aa2f7" alt="GitHub streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=akanjb&theme=tokyo-night&hide_border=true&bg_color=1a1b27&color=7aa2f7&line=bb9af7&point=c0caf5&area=true" width="100%" alt="Contribution graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/akanjb/akanjb/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/akanjb/akanjb/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/akanjb/akanjb/output/github-snake-dark.svg" alt="Contribution snake animation" />
</picture>

</div>

---

<div align="center">

### 💬 Let's build something intelligent

<a href="https://github.com/akanjb"><img src="https://img.shields.io/badge/GitHub-akanjb-1a1b27?style=for-the-badge&logo=github&logoColor=c0caf5" alt="GitHub" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:1a1b27,100:0d1117&height=120&section=footer" width="100%" alt="" />

<sub><i>P.S. This profile is written half-seriously and for fun — VEYRA and the live projects above are the real parts.</i></sub>

</div>
