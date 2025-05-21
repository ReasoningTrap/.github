<!-- Banner -------------------------------------------------------------- -->
<h1 align="center">
  <img src="asset/logo.png" width="48" alt="logo"/>
  ContradictMath • Open-ended Math-Reasoning Benchmarks
</h1>
<p align="center">
  <b>Fine-grain evaluation &amp; RL baselines for large language models that <i>think</i>.</b><br/>
  ConditionedMath (AIME &amp; MATH500) · Model zoo · Training scripts · Zero-shot pipelines
</p>
<p align="center">
  <a href="https://github.com/your-org/ContradictMath/actions">
    <img alt="CI" src="https://github.com/your-org/ContradictMath/actions/workflows/ci.yml/badge.svg"/>
  </a>
  <a href="https://pypi.org/project/contradictmath">
    <img alt="PyPI" src="https://img.shields.io/pypi/v/contradictmath.svg"/>
  </a>
  <a href="LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/your-org/ContradictMath.svg"/>
  </a>
</p>

---

## 📜 Why ReasoningTrap?

> Current RL-tuned LLMs excel at *producing* answers, but often ignore explicit user constraints.  
> **ReasoningTrap** surfaces these failure modes with carefully crafted, *conditioned* problems.

* **Dual tracks** – AIME-style short answers and MATH500 long-form proofs.  
* **RL objective zoo** – GRPO, PRM, Absolute-Zero Reasoner, Eurus-PRIME, ThinkPRM &amp; more.  
* **G-score metric** – geometric mean of correctness, brevity &amp; justification quality.  
* **Plug-and-play** – evaluate any 🤗 Transformers, vLLM or OpenAI-style chat model in two lines.  

---

## 🚀 Quick start
