# Original Paper

Another implementation for: https://arxiv.org/pdf/1803.00191.pdf

Liang Wang. 2018. Yuanfudao at SemEval-2018 Task 11: Three-way Attention and Relational Knowledge for Commonsense Machine Comprehension. (2018). arXiv:arXiv:1803.00191 <MIT License>
  
  
# Introduction

The task assesses how a Three-Way Attentive Network (TriAN) (Liang Wang. 2018. Yuanfudao at SemEval-2018 Task 11) with the inclusion of commonsense knowledge benefits multiple-choice reading comprehension. The combination of attention mechanisms have shown to strongly improve performance for reading comprehension tasks. In addition to that, commonsense knowledge can help in inferring nontrivial implicit events within the comprehension passage. Usually, in addition to what is mentioned in the text, a substantial number of questions in the comprehension task requires inference using common sense knowledge about different everyday scenarios, i.e. answering the questions requires knowledge beyond the facts mentioned in the text. Commonsense knowledge express domain-independent information, and it could complement explicit sentences in the passage by filling in the gaps.


# How to run

```sh
$ CUDA_VISIBLE_DEVICES=0 python trian.py
