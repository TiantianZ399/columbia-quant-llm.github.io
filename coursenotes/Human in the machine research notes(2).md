# Human in the Machine(2)

**Copyright © 2026 Tiantian (Crystal) Zhang and Columbia Quant LLM Club. All rights reserved.**

---

## Core Course Pages

The course should start with these as the backbone:

| Role | Resource |
| --- | --- |
| Main inspiration | Percy Liang’s homepage and research style ([Computer Science][1]) |
| Foundation-model course | Stanford CS324 / Foundation Models ([Stanford CS324][2]) |
| LLM systems course | Stanford CS336: Language Modeling from Scratch ([Stanford CS336][3]) |
| Open foundation-model lab | Marin framework / open lab ([GitHub][4]) |

---

## Chapter 1. Why Study LLMs?

**Core question:** why did scaling plus next-token prediction produce general-purpose intelligence?

**Required readings**

* Stanford CS324: Foundation Models. ([Stanford CS324][2])
* Stanford CS336: Language Modeling from Scratch. ([Stanford CS336][3])
* Percy Liang’s research page / reproducible research philosophy. ([Computer Science][1])
* Marin: open framework for reproducible foundation-model research. ([GitHub][4])

**Seminar thesis:** foundation models should be studied as a scientific object, not only as engineering artifacts.

---

## Chapter 2. Scaling, Compression, and Foundation Models

**Core question:** is intelligence a form of compression?

**Discussion anchors**

* Scaling laws and CS336 training pipeline. ([Stanford CS336][3])
* Marin as a reproducible experimental stack for studying model scaling. ([Marin][5])

**Open questions**

* Is compression the right abstraction for intelligence?
* Are scaling laws empirical regularities or signs of deeper structure?
* Can all disciplines contribute to understanding emergence?

**Seminar note**

When studying the scaling of LLMs, the perspective should be interdisciplinary. All subjects may contribute to understanding scaling laws, emergence, compression, and other phenomena in the pursuit of scientific truth.

---

## Chapter 3. How Transformers Learn Algorithms

**Core question:** do transformers learn algorithms, or shortcuts to algorithms?

**Required readings**

* *Transformers Learn Shortcuts to Automata*. ([arXiv][6])
* Project page for *Transformers Learn Shortcuts to Automata*. ([Clarabing][7])

**CQLLM internal continuation**

* “Partial Answer of How Transformers Learn Automata” — Daniel Hsu course project / CQLLM theory direction. 
* https://arxiv.org/abs/2504.20395 initial course project
* Possible continuation toward an ICML-style submission on automata, linear attention, and algorithm learning.
* Related internal direction: understanding how LLMs learn algorithmic structure and how theory can guide improvements to current architectures.

---

## Chapter 4. Linear Attention and Efficient Architectures

**Core question:** can we beat full attention while preserving expressivity?

**Required readings**

* *Gated Delta Networks: Improving Mamba2 with Delta Rule*. ([arXiv][8])
* Official Gated DeltaNet implementation. ([GitHub][9])
* *Kimi Linear: An Expressive, Efficient Attention Architecture*. ([arXiv][10])
* Kimi Linear GitHub implementation. ([GitHub][11])

**Seminar thesis:** efficient attention is not only a systems question; it is also a question about memory, automata, recurrence, and algorithmic representation.

**CQLLM note**

A Daniel Hsu course project on automata and transformer learning has conceptual overlap with later linear-attention developments. This direction may become a theoretical and experimental paper direction on automata, efficient attention, and algorithm learning.

---

## Chapter 5. Solver or Verifier?

**Core question:** is the next stage of LLM reasoning more about solving, or verifying?

**Required readings**

* LLM-as-a-Verifier project page. ([llm-as-a-verifier on Notion][12])
* LLM-as-a-Verifier GitHub. ([GitHub][13])
* *Beyond Problem Solving: UOJ-Bench for Evaluating Code Generation, Hacking, and Repair in Competitive Programming*. ([arXiv][14])

**Open questions**

* Which open problems can LLMs solve?
* Which open problems can LLMs verify?
* Is verification a more scalable primitive than generation?
* What kinds of open problems can lead us toward the next stage of AGI?

---

## Chapter 6. Post-Training and RL

**Core question:** what actually improves LLMs after pretraining?

**Required readings**

* *Rethinking the Divergence Regularization in LLM RL*. ([arXiv][15])
* Tencent Hunyuan DRPO / UniRL code reference. ([arXiv][16])
* *Simple Policy Optimization*. ([arXiv][17])
* OpenAI Spinning Up: policy optimization background. ([Spinning Up][18])

**Research taste note:** a strong post-training paper often follows:

```text
observe phenomenon
→ make mathematical assumption
→ modify objective
→ verify at scale
```

**Seminar note**

This kind of research taste is especially valuable: elegant observation of a phenomenon, a mathematical assumption, a small but principled modification, and large-scale experimental verification.

---

## Chapter 7. Optimization Beyond Standard RL

**Core question:** what objectives and optimizers should intelligent systems use?

**Required readings**

* *Depth over Fidelity in Fixed-Budget Noisy Evolution Strategies*. ([arXiv][19])
* *Simple Policy Optimization*. ([Proceedings of Machine Learning Research][20])

**Planned topics**

* Muon
* decision-focused learning
* epistemic uncertainty
* agentic optimization
* post-training optimization
* combinatorial optimization

**Seminar direction**

The next section of the seminar will move into optimization, including Muon, decision-focused learning, epistemic uncertainty, agentic optimization, post-training optimization, and combinatorial optimization. Open problems will also be posted.

---

## Chapter 8. Open Problems and Research Taste

**Core seminar questions**

* What open problems can AGI not solve yet?
* What kind of explanation do we want from ML theory?
* Is interpretability useful because it improves finite-data performance?
* What is the objective of explanation?
* How do we distinguish toy benchmark progress from real scientific progress?
* Is an LLM primarily a solver or a verifier?
* Under GPT Pro-level models, is politics harder than math?
* Which areas of math can LLMs solve easily or prove easily?
* What is the harder part of politics?
* Are psychology and philosophy liberal arts, STEM, or fields that demand even higher critical thinking and broader knowledge?

**Working principle**

> Truth is verified iteratively over history. Every theorem, experiment, and failure is an attempt to approximate truth.

**Seminar note**

Machine learning theory faces a difficult situation: some phenomena were invented before they were explained. Neural networks optimize successfully, but the explanation remains incomplete. We therefore need to ask what kind of interpretability or explanation we actually want, and what objective such explanation serves.

---

## Chapter 9. Art, Philosophy, Virtuality, and Reality

**Core thesis:** philosophy gives the guiding rules before mathematics formalizes them.

**Discussion themes**

* academia as a virtual world that predicts reality
* theory as prediction
* art as condensed history
* human art as experiment in social idealism
* world model vs language model
* free will, determinism, intuition, and taste
* virtual world versus real world
* academia as a predictive abstraction of reality

**CQLLM working view**

Theorists are predictors. Engineers make predictions real. Industry distributes them. The public sustains the whole system.

**Seminar position**

Philosophy is not separate from science. Philosophy defines objectives, assumptions, and evaluation criteria before mathematics begins.

**Art and civilization note**

Art can be understood as a condensation of history and of human civilization. Fine art may touch living creatures through music, dance, and visual experience, while human civilizational art — literature, film, theater, writing — condenses the history, idealism, and experiments of society.

---

## Chapter 10. Determinism, Free Will, and Prediction

**Discussion theme**

Can the future be predicted? Is the world deterministic? Is human life a Markov process?

**Seminar discussion**

One perspective argues that if everything is predictable, then sufficiently powerful AI could in principle solve future prediction. However, such a machine would be dangerous for individuals and society because it could collapse ordinary value systems.

Another perspective is that academia as a virtual world predicts reality not because the world is literally a Markov chain, but because events have origins, rationales, and logical chains. Love and hatred have causes; every event has a rationale. Philosophy can serve as guiding rules for interpreting these chains.

**Working view**

Human free will can be understood as the weaving together of intuition and taste. A person’s path may move from uniqueness toward idealism. Theoretical researchers, in this sense, are predictors.

---

## Chapter 11. Society, Idealism, and Research

**Core question:** what kind of society better punishes harm and encourages good?

**Discussion themes**

* society as mutual support
* inequality of origins and equality of created dignity
* each person living through their uniqueness
* each person pursuing idealism through their own algorithm
* policy design as a way to punish evil and stimulate good
* the relationship between philosophy, politics, society, and AI

**Seminar view**

We live in a mutually supporting society. Theorists make discoveries. Engineers and researchers turn them into reality. Industry workers push them to the public. The public supports the entire system.

---

## Chapter 12. Practical Seminar Notes and Announcements

**Upcoming focus**

The next major section will focus on optimization:

* Muon
* decision-focused learning
* epistemic uncertainty
* agentic optimization
* post-training optimization
* combinatorial optimization

**Related note**

Research note: *The Return of Market Uncertainty and the Prediction Paradox.*

---

## Appendix A. Resource Index

### Courses and websites

* Percy Liang homepage. ([Computer Science][1])
* Stanford CS324 Foundation Models. ([Stanford CS324][2])
* Stanford CS336 Language Modeling from Scratch. ([Stanford CS336][3])
* Marin open lab. ([Marin][21])
* Marin GitHub. ([GitHub][4])
* CQLLM course webpage. ([GitHub][22])
* Tiantian Zhang academic webpage. ([Personal Website][23])
* CQLLM mailing list. ([Google Forms][24])

### Papers and projects

* *Transformers Learn Shortcuts to Automata*. ([arXiv][6])
* *Gated Delta Networks*. ([arXiv][8])
* *Kimi Linear*. ([arXiv][10])
* *Rethinking the Divergence Regularization in LLM RL*. ([arXiv][15])
* *Simple Policy Optimization*. ([Proceedings of Machine Learning Research][20])
* *Depth over Fidelity in Fixed-Budget Noisy Evolution Strategies*. ([arXiv][19])
* *Beyond Problem Solving: UOJ-Bench*. ([arXiv][14])
* LLM-as-a-Verifier. ([llm-as-a-verifier on Notion][12])

### Additional discussion references

* Foundation model concept. ([Wikipedia][25])
* OpenAI Spinning Up policy optimization background. ([Spinning Up][18])
* Tencent Hunyuan DRPO / UniRL reference. ([arXiv][16])

---

## Disclaimer and License

These notes are based on seminar discussions and comments within Columbia Quant LLM. They are provided for educational and research purposes.

All comments and notes may not be reposted, redistributed, or used for commercial or intermediary purposes without explicit permission.

**Copyright © 2026 Tiantian (Crystal) Zhang and Columbia Quant LLM Club. All rights reserved.**

---

## Mailing List

Subscribe to the CQLLM mailing list:

https://docs.google.com/forms/d/e/1FAIpQLScerOMffYiH3oKWe-lhsFRF5BrOvWep5wHZDiJhUDlLFkGGxw/viewform?usp=header

---

[1]: https://cs.stanford.edu/~pliang/ "Percy Liang - Stanford Computer Science"
[2]: https://stanford-cs324.github.io/winter2023/ "CS 324 - Advances in Foundation Models"
[3]: https://cs336.stanford.edu/ "Stanford CS336 | Language Modeling from Scratch"
[4]: https://github.com/marin-community/marin "marin-community/marin"
[5]: https://marin.community/blog/2025/05/19/announcement/ "Introducing Marin: An Open Lab for Building Foundation Models"
[6]: https://arxiv.org/abs/2210.10749 "Transformers Learn Shortcuts to Automata"
[7]: https://clarabing.github.io/shortcut_automata/ "Transformers Learn Shortcuts to Automata"
[8]: https://arxiv.org/abs/2412.06464 "Gated Delta Networks: Improving Mamba2 with Delta Rule"
[9]: https://github.com/NVlabs/GatedDeltaNet "Official PyTorch Implementation of Gated Delta Networks"
[10]: https://arxiv.org/abs/2510.26692 "Kimi Linear: An Expressive, Efficient Attention Architecture"
[11]: https://github.com/MoonshotAI/Kimi-Linear "MoonshotAI/Kimi-Linear"
[12]: https://llm-as-a-verifier.notion.site/ "LLM-as-a-Verifier"
[13]: https://github.com/llm-as-a-verifier/llm-as-a-verifier "LLM-as-a-Verifier GitHub"
[14]: https://arxiv.org/abs/2606.12864 "Beyond Problem Solving: UOJ-Bench"
[15]: https://arxiv.org/abs/2606.09821 "Rethinking the Divergence Regularization in LLM RL"
[16]: https://arxiv.org/pdf/2606.09821 "Rethinking the Divergence Regularization in LLM RL PDF"
[17]: https://arxiv.org/abs/2401.16025 "Simple Policy Optimization"
[18]: https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html "Part 3: Intro to Policy Optimization - Spinning Up in Deep RL"
[19]: https://arxiv.org/abs/2606.06555 "Depth over Fidelity in Fixed-Budget Noisy Evolution Strategies"
[20]: https://proceedings.mlr.press/v267/xie25m.html "Simple Policy Optimization"
[21]: https://marin.community/ "Marin"
[22]: https://github.com/TiantianZ399/columbia-quant-llm.github.io "Columbia Quant LLM course webpage"
[23]: https://tiantianz399.github.io/preview.html "Tiantian Zhang academic webpage"
[24]: https://docs.google.com/forms/d/e/1FAIpQLScerOMffYiH3oKWe-lhsFRF5BrOvWep5wHZDiJhUDlLFkGGxw/viewform?usp=header "CQLLM mailing list"
[25]: https://en.wikipedia.org/wiki/Foundation_model "Foundation modeHun"
