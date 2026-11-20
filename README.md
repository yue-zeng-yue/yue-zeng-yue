<div align="center">
  <a href="https://github.com/yue-zeng-yue">
    <img src="assets/banner.png" alt="A warm orange retro terminal banner for yue — LLM systems engineer" width="100%" />
  </a>
  <br />
  <br />
  <a href="#about"><code>$ about</code></a> &nbsp;·&nbsp;
  <a href="#work"><code>$ work</code></a> &nbsp;·&nbsp;
  <a href="#projects"><code>$ projects</code></a> &nbsp;·&nbsp;
  <a href="#notes"><code>$ notes</code></a> &nbsp;·&nbsp;
  <a href="#contact"><code>$ contact</code></a>
</div>

<br />

## about

```console
~/yue $ whoami
yue — LLM Systems Engineer

~/yue $ cat background.txt
M.IT  ·  University of New South Wales (UNSW)
LLM Algorithm Engineer  ·  CMB
```

I work on **training and improving language models** — from reinforcement learning algorithms to the systems that make experiments reproducible, efficient, and practical.

Most of my work sits at the intersection of **agentic reinforcement learning, distributed training, optimization, and self-improving AI systems**. I enjoy understanding both the mathematical ideas and the engineering details required to make them work.

## work

```console
~/yue $ ls research/
agentic-rl/
training-systems/
efficient-optimization/
self-improving-agents/
```

| Area | What I explore |
| :-- | :-- |
| **Agentic RL** | GRPO and policy optimization, reward design, rollout / actor pipelines, and evaluation. |
| **Training systems** | FSDP2, distributed execution, checkpointing, and GPU / NPU training infrastructure. |
| **Efficient optimization** | Optimizers, LoRA, low-rank gradient methods, and memory–throughput trade-offs. |
| **Self-improving agents** | Harness RSI, execution feedback, controlled experiments, and improvement that transfers to unseen tasks. |

The questions I keep coming back to are simple: *Does it work? Why does it work? What does it cost? Can someone reproduce it?*

## projects

```console
~/yue $ ls -la selected-work/
```

| Repository | Notes |
| :-- | :-- |
| **[sft-autoresearch](https://github.com/yue-zeng-yue/sft-autoresearch)** | A bounded AutoResearch-style SFT configuration and evaluation loop built around the ms-swift backend. |
| **[rsi-research-hub](https://github.com/yue-zeng-yue/rsi-research-hub)** | A research library for recursive self-improvement: literature, hypotheses, benchmark design, and reproducibility protocols. |
| **[verl (working fork)](https://github.com/yue-zeng-yue/verl)** | My workspace for exploring RL training infrastructure and integration experiments in the community-developed verl framework. |
| **[ms-swift-aero (working fork)](https://github.com/yue-zeng-yue/ms-swift-aero)** | My workspace around the ModelScope ms-swift ecosystem and training-system experiments. |

<sub>Credit: <a href="https://github.com/verl-project/verl">verl</a> and <a href="https://github.com/modelscope/ms-swift">ms-swift</a> are community projects. The linked working copies are not claims of authorship of the upstream frameworks.</sub>

## notes

```console
~/yue $ cat current-focus.md
[1] Efficient RL training for language models
[2] Optimizer design and low-rank updates
[3] Reliable evaluation of self-improving agent systems
```

I care about **measured improvements**, not just attractive benchmark numbers. That means controlled baselines, real workload traces, repeatable runs, ablations, and transparent reporting of what did *not* improve.

**Tools I reach for:** Python · PyTorch · VERL · ms-swift · vLLM · Ray · FSDP2 · Hugging Face · Qwen

## contact

```console
~/yue $ echo 'open to thoughtful discussions about LLM training and AI systems'
open to thoughtful discussions about LLM training and AI systems
```

You can find my public work and reach me through **[GitHub](https://github.com/yue-zeng-yue)**.

---

<div align="center">
  <sub><code>~/yue $ keep_building_</code></sub>
</div>
