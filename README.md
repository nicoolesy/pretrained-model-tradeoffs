# Picking the Right Pre-Trained Model

A single-page, interactive infographic comparing **six pre-trained models** across
**three domains** (NLP/Generative AI, Computer Vision, Tabular Data) on the trade-offs
that actually govern deployment: **size, accuracy, and speed**, plus interpretability,
The consideration that matters most when a decision has to be explained.

🔗 **Live page:** [View it here](https://nicoolesy.github.io/pretrained-model-tradeoffs/)

---

## What's in here

| File | Purpose |
|------|---------|
| `index.html` | The complete artifact — self-contained HTML/CSS/JS, no build step, no dependencies beyond Google Fonts |
| `README.md` | This file — context, sources, design rationale, and the submission checklist |

The page is fully responsive, keyboard-accessible (the domain filter is operable with
Tab + Enter/Space), and respects `prefers-reduced-motion`.

---

## The artifact at a glance

- **Interactive decision matrix** — filter the six models by domain to isolate a comparison.
- **Four scored axes** — Size, Accuracy, Inference Speed, Interpretability, plus a "Best Fit" call.
- **Source integrity built in** — every cell is tagged:
  - 🟢 **Sourced** — an exact published figure from the model's original paper.
  - 🔴 **Characterized** — a qualitative rating that depends on hardware, dataset, or task and has no single comparable benchmark.
- **Analysis + recommendations** — why the three axes pull against each other, and what to pick per domain.

---

## The models & where the numbers come from

> **Citation integrity note.** Parameter counts and ImageNet top-1 accuracy below are
> **exact figures from the original publications**. Inference speed, interpretability, and
> tabular accuracy are **characterizations**, not single benchmark values — they vary by
> hardware and dataset, and are labelled that way throughout the artifact.

| Model | Domain | Sourced figure(s) | Primary source |
|-------|--------|-------------------|----------------|
| GPT-3 | NLP/GenAI | 175B parameters | Brown et al. (2020) |
| BERT-base | NLP | 110M parameters | Devlin et al. (2019) |
| MobileNetV2 | Vision | 3.4M params · 72.0% ImageNet top-1 | Sandler et al. (2018) |
| EfficientNet-B7 | Vision | 66M params · 84.3% ImageNet top-1 | Tan & Le (2019) |
| XGBoost | Tabular | tree ensemble (no fixed param count) | Chen & Guestrin (2016) |
| LightGBM | Tabular | tree ensemble (no fixed param count) | Ke et al. (2017) |

### References (APA 7th)

- Brown, T. B., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., Dhariwal, P., … Amodei, D. (2020). *Language models are few-shot learners* [GPT-3]. arXiv:2005.14165.
- Chen, T., & Guestrin, C. (2016). *XGBoost: A scalable tree boosting system*. Proceedings of KDD 2016. arXiv:1603.02754.
- Devlin, J., Chang, M.-W., Lee, K., & Toutanova, K. (2019). *BERT: Pre-training of deep bidirectional transformers for language understanding*. Proceedings of NAACL-HLT 2019. arXiv:1810.04805.
- Ke, G., Meng, Q., Finley, T., Wang, T., Chen, W., Ma, W., … Liu, T.-Y. (2017). *LightGBM: A highly efficient gradient boosting decision tree*. Advances in Neural Information Processing Systems 30.
- Sandler, M., Howard, A., Zhu, M., Zhmoginov, A., & Chen, L.-C. (2018). *MobileNetV2: Inverted residuals and linear bottlenecks*. Proceedings of CVPR 2018. arXiv:1801.04381.
- Tan, M., & Le, Q. V. (2019). *EfficientNet: Rethinking model scaling for convolutional neural networks*. Proceedings of ICML 2019. arXiv:1905.11946.

---

## Design rationale

This is **Vol. 04** in the editorial portfolio series and reuses the established system so
the body of work reads as one publication:

- **Type** — Playfair Display (headlines), Source Serif 4 (body), Crimson Pro italic (accents/callouts), JetBrains Mono (labels & data).
- **Palette** — cream `#ECE5D6` ground, oxblood `#9C2B26` accent, near-black `#1C1714` ink.
- **Structure** — dotted-grid background, hairline rules, `§ 0X —` section markers.
- **Domain colour-coding** — blue (NLP), amber (Vision), green (Tabular), echoing the Vol. 03 phase dots.

The one new idea this volume introduces is the **Sourced / Characterized tagging system** —
a visible way to separate hard published figures from qualitative judgments. It directly
supports the assignment's emphasis on explainability and honest methodology, and it's the
"signature" element of this piece.

---

## Mapping to the rubric

| Rubric criterion | Where it's addressed |
|------------------|----------------------|
| Clarity & Organization | `§ 01–04` structure; filter isolates one comparison at a time |
| Visual Appeal & Professionalism | consistent editorial system carried from Vols. 01–03 |
| Technical Execution | self-contained, responsive, accessible (keyboard + reduced-motion) |
| Classification Accuracy | models grouped by domain; within- vs across-domain distinction made explicit |
| Representation of Relationships | matrix + rating bars + recommendation rows |
| Comprehensiveness | size/accuracy/speed/interpretability + best-fit, across all 3 domains |
| Explanation of Classification Process | `§ 04 Method & Sources` explains selection + sourcing logic |
| Reflection on Learning | *to be added by you — see checklist* |
| Writing Quality | concise editorial copy throughout |


