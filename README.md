# Alibi Serikbay

AI engineer in Astana, Kazakhstan.

Kazakh is still underserved by open speech recognition. I trained models for Kazakh, Russian, and speech that switches between them, and released the weights with evaluation details and limitations.

## Work

- **[Kazakh & Russian STT](https://huggingface.co/alibiserikbay/kazakh-russian-mixed-stt)** — three TorchScript recognizers, including one for mixed-language audio. [CPU inference example on GitHub](https://github.com/allebee/kazakh-russian-mixed-stt).
- **[JevK5](https://github.com/allebee/jevk5)** — an open decision model for yes/no, choice, and score questions, returning calibrated probabilities in one pass.
- **[pytest-jev](https://github.com/allebee/pytest-jev)** — pytest assertions for what an LLM response means, with probabilities in test failures.
- **[jevgrep](https://github.com/allebee/jevgrep)** — filters live logs by meaning using plain-English yes/no questions.

If you test the speech model on real Kazakh or mixed-language audio, I'd like to hear where it fails. [Report an STT error](https://github.com/allebee/kazakh-russian-mixed-stt/issues) or [contact me on LinkedIn](https://www.linkedin.com/in/alibi-serikbay/).
