[Poly-encoders: Transformer Architectures and Pre-training Strategies for Fast and Accurate Multi-sentence Scoring](https://arxiv.org/abs/1905.01969)

submitted ICLR 2020

## Task
Candidate Retrieval and Scoring

## Research Question

* How to combine both of the merits of Bi-encoder and cross-encoder?

  * The former is fast but low performance, while the latter vise versa.

## Approach

* Cache both of the representations of mention and candidates, but also add attention layer after encoding context.

---

## memo

* Also trying another pre-training strategy.

  * Use datasets, e.g. reddit., similar to the downstream task.

## Slides (Unofficial)

* [link](https://speakerdeck.com/izuna385/poly-encoders-transformer-architectures-and-pre-training-strategies-for-fast-and-accurate-multi-sentence-scoring)
