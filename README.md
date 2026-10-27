# dl-from-scratch

My study log for the Japanese book series **『ゼロから作る Deep Learning』**
(*Deep Learning from Scratch*, O'Reilly Japan, by Koki Saitoh), volumes ❶ to ❻.

I work through the books chapter by chapter, typing and running the code myself
rather than copying it, and add my own notes, experiments, and small variations
along the way. The goal is to understand deep learning from first principles —
from a NumPy-only neural network up to a working framework, RL agents,
generative models, and LLMs.

## The series

| Vol | Japanese title | Topic |
| --- | --- | --- |
| ❶ | ゼロから作る Deep Learning | Neural network basics with NumPy only: perceptrons, backpropagation, optimizers, CNNs |
| ❷ | 自然言語処理編 | NLP: word2vec, RNN / LSTM, seq2seq, attention |
| ❸ | フレームワーク編 | Building a deep learning framework (DeZero) step by step: autograd, dynamic graphs |
| ❹ | 強化学習編 | Reinforcement learning: bandits, MDPs, DP, Monte Carlo, TD, DQN, policy gradients |
| ❺ | 生成モデル編 | Generative models: Gaussian mixtures, EM, VAE, diffusion models |
| ❻ | LLM編 | Large language models: tokenization, Transformers, GPT-style models (2026) |

## Layout

One directory per volume, one subdirectory per chapter, with two-digit numbers:

```
vol1/
  ch03/   # ❶ chapter 3
  ch04/
vol3/
  step01/ # ❸ is organized in "steps" instead of chapters
```

- `volN/chMM/` — volume `N` (1–6), chapter `MM` (`01`, `02`, ...).
- Volumes ❸ and ❺ are organized by **steps** in the books, so they use
  `volN/stepMM/` instead (e.g. `vol3/step12/`).
- Shared helpers for a volume go in `volN/common/`.

Chapter directories are created when I start a chapter, not ahead of time.

## Progress

| Vol | Status | Furthest chapter | Notes |
| --- | --- | --- | --- |
| ❶ | in progress | – | |
| ❷ | not started | – | |
| ❸ | not started | – | |
| ❹ | not started | – | |
| ❺ | not started | – | |
| ❻ | not started | – | |

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Credits and licensing

The code here follows the official sample code published by O'Reilly Japan,
which is released under the MIT License:

- [oreilly-japan/deep-learning-from-scratch](https://github.com/oreilly-japan/deep-learning-from-scratch) (❶)
- [oreilly-japan/deep-learning-from-scratch-2](https://github.com/oreilly-japan/deep-learning-from-scratch-2) (❷)
- [oreilly-japan/deep-learning-from-scratch-3](https://github.com/oreilly-japan/deep-learning-from-scratch-3) (❸)
- [oreilly-japan/deep-learning-from-scratch-4](https://github.com/oreilly-japan/deep-learning-from-scratch-4) (❹)
- [oreilly-japan/deep-learning-from-scratch-5](https://github.com/oreilly-japan/deep-learning-from-scratch-5) (❺)
- [oreilly-japan/deep-learning-from-scratch-6](https://github.com/oreilly-japan/deep-learning-from-scratch-6) (❻)

The book text, figures, and explanations are **not** reproduced here — please
buy the books. My own code and notes in this repository are MIT licensed
(see [LICENSE](LICENSE)).
