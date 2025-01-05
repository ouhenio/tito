# tito: _un modelo chiquitito_

This project attempts to create a **spanish small language model**. Its an educative project, not an attempt to create a SoTA.

Current roadmap:

- [x] Pretrain a 135M GPT on a subset of [red-pajama_es_hq](https://huggingface.co/datasets/latam-gpt/red_pajama_es_hq).
  - [Trained a first version](https://huggingface.co/ouhenio/tito). 😊
- [x] Add instruction finetunning.
  - Translated 30k instructions from [smoltalk](https://huggingface.co/datasets/HuggingFaceTB/smoltalk) to spanish. [Here is the dataset](https://huggingface.co/datasets/ouhenio/smoltalk-es). It will be increased to 150k soon.
  - [Did SFT on said 30k instructions](https://huggingface.co/ouhenio/tito-sft).
- [ ] Add DPO.

---

_This project is dedicated to the memory of Tito, a beautiful cat._
