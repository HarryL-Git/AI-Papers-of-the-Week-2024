# AI Papers of The Week

As a researcher, I frequently read AI papers and am trying to create this repository to record some highlighted AI papers that I read each week.

Here is the weekly series:

## 2024

- [AI Papers of the Week (April 8 - April 14)](./#ai-papers-of-the-week-april-15---april-21---2024)

## AI Papers of the Week (April 15 - April 21) - 2024
| **Paper**  | **Links** |
| ------------- | ------------- |
| 1) **ReFT: Representation Finetuning for Language Models** - Parameter-efficient fine-tuning (PEFT) methods seek to adapt large models via updates to a small number of weights. However, much prior interpretability work has shown that representations encode rich semantic information, suggesting that editing representations might be a more powerful alternative. Here, we pursue this hypothesis by developing a family of Representation Finetuning (ReFT) methods. ReFT methods operate on a frozen base model and learn task-specific interventions on hidden representations. We define a strong instance of the ReFT family, Low-rank Linear Subspace ReFT (LoReFT). LoReFT is a drop-in replacement for existing PEFTs and learns interventions that are 10×–50× more parameter-efficient than prior state-of-the-art PEFTs. We showcase LoReFT on eight commonsense reasoning tasks, four arithmetic reasoning tasks, Alpaca-Eval v1.0, and GLUE. In all these evaluations, LoReFT delivers the best balance of efficiency and performance, and almost always outperforms state-of-the-art PEFTs.  | [Paper](https://arxiv.org/abs/2404.03592), [Repo](https://github.com/stanfordnlp/pyreft)|
