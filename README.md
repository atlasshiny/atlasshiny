# Hey, I'm Manuel!

**Computer Engineering & Mathematics @ University of Florida**

I work on high-performance computing, GPU kernels, and ML systems, mostly where they meet quantitative finance.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-manuelosoriocpe-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuelosoriocpe/)
[![Email](https://img.shields.io/badge/Email-osoriom%40ufl.edu-D14836?logo=gmail&logoColor=white)](mailto:osoriom@ufl.edu)

---

## What I'm doing now

- **Undergraduate AI Researcher** at the UF Warrington Fintech Research Center (advised by Dr. Yanbin Wu). I'm building an interpretability pipeline on the HiPerGator supercomputer to evaluate LLM reasoning faithfulness in algorithmic backtesting. I also wrote a fused Triton kernel (RMSNorm + linear projection) that cut per-pass latency from 120 ms to 19 ms (**6.22x**).
- **Co-Founder & Technical Lead at Sandhiva**, a local-first clinical support tool (accepted into the Gator Hatchery). It runs a fully on-device RAG backend with in-memory PHI scrubbing, so patient data never leaves the machine.

## Projects

### [Greeks Engine](https://github.com/atlasshiny/greeks-engine)
A header-only C++20/CUDA option-pricing library with Black-Scholes-Merton, Binomial Tree, and Monte Carlo models, plus all five Greeks (Δ, Γ, ν, θ, ρ). It has Lean 4 verified invariants and reaches up to **4x (BSM) / 18.5x (Binomial Tree)** GPU speedup over single-threaded CPU. Profiled with Google Benchmark and Nsight.
![C++20](https://img.shields.io/badge/C++20-00599C?logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) ![Lean 4](https://img.shields.io/badge/Lean_4-5A2D82) ![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white) ![Nsight](https://img.shields.io/badge/Nsight-76B900?logo=nvidia&logoColor=white) ![Google Benchmark](https://img.shields.io/badge/Google_Benchmark-4285F4?logo=google&logoColor=white)

### [Custom Order Book System](https://github.com/atlasshiny/Order-Book-System)
A C++20 TCP exchange simulator built on Boost.ASIO and deployed on a Raspberry Pi 5, with multiple order books and users. It uses a partial FIX protocol implementation with zero-copy parsing via `std::string_view`, state-machine orchestration and risk management, and a Python client SDK.
![C++20](https://img.shields.io/badge/C++20-00599C?logo=cplusplus&logoColor=white) ![Boost.ASIO](https://img.shields.io/badge/Boost.ASIO-1A1A1A) ![FIX Protocol](https://img.shields.io/badge/FIX_Protocol-444444) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Raspberry Pi 5](https://img.shields.io/badge/Raspberry_Pi_5-A22846?logo=raspberrypi&logoColor=white)

### [SocraticGraph](https://github.com/atlasshiny/socraticgraph)
A multi-agent Socratic tutor built with LangGraph and LangChain that runs on open-source models within consumer VRAM limits. It uses asymmetric model routing: small, precise models (Phi-4-Mini) for schema parsing and larger models (Llama-3.1, Mistral) for generation.
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white) ![Llama.cpp](https://img.shields.io/badge/Llama.cpp-444444) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

### Gator Quant Hacks (Oct 2026)
A hybrid predictive pipeline for time-series data: a genetic algorithm for feature search and hyperparameter tuning feeding an XGBoost model, with multi-GPU PyTorch DDP training and a fused Triton kernel on an NVIDIA B200 (Blackwell).
![PyTorch DDP](https://img.shields.io/badge/PyTorch_DDP-EE4C2C?logo=pytorch&logoColor=white) ![Triton](https://img.shields.io/badge/Triton-76B900?logo=nvidia&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189AB4) ![Polars](https://img.shields.io/badge/Polars-CD792C?logo=polars&logoColor=white)
<!-- TODO: add repo link -->

<!--
## 📊 GitHub Stats

<p align="center">
  <img height="170" alt="Manuel's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=atlasshiny&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="170" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=atlasshiny&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</p>

<p align="center">
  <img alt="GitHub streak" src="https://streak-stats.demolab.com?user=atlasshiny&theme=tokyonight&hide_border=true" />
</p>
-->

## Research Interests

High-performance computing · CUDA kernel acceleration · Mechanistic interpretability · Modeling systems & phenomena · Formal methods & verification (Lean 4) · Agentic AI

## Contact

Open to talking about GPU performance, quant systems, and interpretability. Email me at [osoriom@ufl.edu](mailto:osoriom@ufl.edu) or find me on [LinkedIn](https://www.linkedin.com/in/manuelosoriocpe/).
