# Howdy, I'm Daniel 👋.

I'm a Senior Machine Learning Software Engineer focused on reinforcement learning, ML systems, and research infrastructure.

I enjoy turning research ideas into working systems: implementing algorithms from first principles, designing controlled experiments, and building reliable infrastructure for machine learning.

[![Claude](https://img.shields.io/badge/Claude-D97757?logo=claude&logoColor=fff)](#) [![Google Gemini](https://img.shields.io/badge/Google%20Gemini-886FBF?logo=googlegemini&logoColor=fff)](#) [![Cursor](https://img.shields.io/badge/Cursor-000000?logo=cursor)](#) [![NumPy](https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff)](#) [![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](#) [![JAX](https://custom-icon-badges.demolab.com/badge/JAX-222827?logo=jax&logoColor=ffffff)](#) [![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=fff)](#) [![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff)](#) [![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#) [![C++](https://img.shields.io/badge/C++-%2300599C.svg?logo=c%2B%2B&logoColor=white)](#) [![Rust](https://img.shields.io/badge/Rust-%23000000.svg?e&logo=rust&logoColor=white)](#) [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000)](#)

## Featured Projects

### Reinforcement Learning Research

**[kairos](https://github.com/dantp-ai/kairos)** — *Learning under real-time compute constraints*

Investigates reinforcement learning when the environment cannot wait for the learner. Implements bounded-compute PPO with stale policies and dropped experience, using controlled experiments to study the trade-off between additional optimization epochs and fresher training data.

### Scientific Machine Learning

**[orbscreen](https://github.com/dantp-ai/orbscreen)** — *Uncertainty-aware materials screening at scale*

Deep-ensemble graph neural network surrogate for predicting Orb-v3 relaxed-state MOF stability from unrelaxed structures. Halves energy MAE relative to a descriptor baseline, achieves ~6–7× top-decile enrichment, and uses selective simulation to reduce screening costs by 5–6.6×. Built using [Modal](https://modal.com/), [Orb-v3](https://huggingface.co/papers/2504.06231), and [MofasaDB](https://huggingface.co/datasets/Orbital-Materials/MofasaDB).

### ML Systems

**[minitorch](https://github.com/dantp-ai/minitorch)** — *Deep learning framework from first principles*

Implements automatic differentiation, multidimensional tensors, neural network operations, and computation backends using NumPy, parallel Numba CPU kernels, and CUDA. Explores the abstractions and performance trade-offs underlying modern deep learning frameworks.

### Research Infrastructure

**[AlphaEx](https://github.com/dantp-ai/AlphaEx)** — *Distributed experiment orchestration*

Python tooling for launching parameter sweeps and coordinating thousands of Slurm jobs across research compute clusters. Designed to make large-scale experimentation easier to configure, execute, and reproduce.

## More Projects

### Reinforcement Learning & Robotics

- **[proprio](https://github.com/dantp-ai/proprio)** — Unsupervised, uncertainty-aware perception for a 7-DOF robotic arm. Classifies lidar readings as self, background, or anomalies without relying on explicit robot geometry or kinematics.
- **[gym-puddle](https://github.com/dantp-ai/gym-puddle)** — Gymnasium Puddle World environment with an example off-policy reinforcement learning agent implemented using [TorchRL](https://github.com/pytorch/rl).
- **[STOMP paper reimplementation](https://github.com/dantp-ai/reward-respecting-subtasks-jax)** — JAX implementation exploring reward-respecting subtasks and state construction.

### AI Evaluation & Applications

- **[medical-jiwer](https://github.com/dantp-ai/medical-jiwer)** — Medical speech-recognition evaluation built on JiWER, including medical-term WER, entity F1, and occurrence-aware scoring for doses, negation, and other clinically important values.
- **[BetterNǎo](https://github.com/dantp-ai/neurohackathon2026)** — Hackathon prototype exploring EEG foundation-model embeddings for wellness monitoring, with a React Native interface for viewing signals and annotations.
- **[priori](https://github.com/dantp-ai/priori)** — [Interactive benchmark](https://dantp-ai.github.io/priori/) comparing tabular foundation models (TabPFN v2 and Google TabFM) against tuned XGBoost and AutoGluon on churn and credit datasets.

### Systems & Technical Explorations

- **[internals](https://dantp-ai.github.io/internals/)** — Interactive, first-principles explanations of modern AI systems, including a [visual walkthrough of speculative decoding](https://dantp-ai.github.io/internals/speculative-decoding/).
- **[nabla](https://github.com/dantp-ai/nabla)** — NumPy implementations of 15 optimization algorithms, from SGD to Muon, with animated optimization trajectories and matrix least-squares benchmarks.
- **[map-reduce-distributed-grpc](https://github.com/dantp-ai/map-reduce-distributed-grpc)** — Distributed MapReduce implementation using gRPC, with a coordinator dispatching map and reduce tasks to worker processes.

### Other Software

- **[cloze](https://github.com/dantp-ai/cloze)** — Self-hosted language-learning application that generates fill-in-the-blank exercises from personal sentences and schedules reviews using SM-2 spaced repetition. Built with Next.js and PostgreSQL.

## Technical Writing

- [Review of the Gemini Robotics 1.5 Technical Report](https://therewardsignal.substack.com/p/review-of-the-technical-report-on-gemini-robotics-1-5)
