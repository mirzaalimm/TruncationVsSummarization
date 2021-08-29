# Truncation Vs Summarization
This repository contains the implementation of our paper\*: \
M. A. Mutasodirin, R. E. Prasojo, *"Investigating Text Shortening Strategy in BERT: Truncation vs Summarization"*, 2021. \
\*Under consideration for presentation at The 13th International Conference on Advanced Computer Science and Information Systems (ICACSIS) 2021.

# Abstract
The parallelism of Transformer-based models comes at the cost of their input max-length. Some studies proposed methods to overcome this limitation, but none of them reported the effectiveness of summarization as an alternative. In this study, we investigate the performance of document truncation and summarization in text classification tasks. Each of the two was investigated with several variations. This study also investigated how close their performances are to the performance of full-text. We used a dataset of summarization tasks based on Indonesian news articles (IndoSum) to do classification tests. This study shows how the summaries outperform the majority of truncation method variations and lose to only one. The best strategy obtained in this study is taking the head of the document. The second is extractive summarization. This study explains what happened to the result, leading to further research in order to exploit the potential of document summarization as a shortening alternative. The code and data used in this work are publicly available in https://github.com/mirzaalimm/TruncationVsSummarization.

# Keywords
long text, document classification, summarization, shortening strategy, BERT.

# Data
Original IndoSum: [Link 1](https://drive.google.com/file/d/1OgYbPfXFAv3TbwP1Qcwt_CC9cVWSJaco/view), [Link 2](https://github.com/kata-ai/indosum), [Alt. Link](https://drive.google.com/file/d/1jPHVCx33-nseIKdLV8lBu6SCwESwl0te/view?usp=sharing). \
Ready-to-Use Filtered-IndoSum: [Link 1](). \
Ready-to-Use Automatic Abstractive Summaries: [Link 1]().

# Code
IndoSum Statistics: [Link 1](), [Alt. Link]() \
Filtering IndoSum: [Link 1](), [Alt. Link]() \
Automatic Abstractive Summarization:  [Link 1](), [Alt. Link]() \
Filtered-IndoSum Statistics: [Link 1](), [Alt. Link]() \
Document Classification: [Link 1](), [Alt. Link]()

# License
MIT
