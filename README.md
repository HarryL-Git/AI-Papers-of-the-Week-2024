# AI Papers of The Week

As a researcher, I frequently read AI papers and am trying to create this repository to record some highlighted AI papers that I read each week.

Here is the weekly series:

## 2024

- [AI Papers of the Week (April 8 - April 14)](./#ai-papers-of-the-week-april-15---april-21---2024)

## AI Papers of the Week (April 15 - April 21) - 2024
| **Paper**  | **Links** |
| ------------- | ------------- |
| 1) **ReFT: Representation Finetuning for Language Models** - This paper proposes a novel method for parameter-efficient fine-tuning of language models called Representation Finetuning (ReFT). This method focuses on task-specific adjustments to hidden representations within a frozen base model, unlike traditional approaches that update a small subset of model weights. ReFT introduces Low-rank Linear Subspace ReFT (LoReFT), which is significantly more efficient than existing methods, requiring up to 50 times fewer parameters. The paper demonstrates LoReFT's superior performance across several tasks, including commonsense and arithmetic reasoning, as well as benchmarks like GLUE and Alpaca-Eval v1.0, consistently outperforming other fine-tuning approaches. A generic ReFT training library has also been made publicly available.   | [Paper](https://arxiv.org/abs/2404.03592), [Repo](https://github.com/stanfordnlp/pyreft)|
