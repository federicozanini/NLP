[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
# NLP - Project
Università di Bologna A.A. 2020/2021

## Abstract
These investigations aimed to create an NLP system that, given a paragraph and a question regarding it, provides a single answer, which is obtained by selecting a span of text from the paragraph itself. The dataset we used is SQuAD - The Stanford Question Answering Dataset which contains 100,000+ question-answer pairs on 500+ articles.
We applied many different strategies in order to progressively understand and cope with the different aspects of the task. We started out with many traditional RNNs approaches with the addition of different attention layers; then, we tried to improve our results through more systemic data preprocessing exploiting ELMo model; afterwards, we implemented a more complex model, following academic paper BiDirectional Attention Flow; eventually we approached state-of-the-art Bert model performing its fine-tuning and attaching different heads.
Performance evaluation for each of these approaches had been checked with the given evaluation.py testing method, in accordance with the request of the examiners.

### Authors
- Allegra Adinolfi
- Matteo Folli
- Lucia La Forgia
- Federico Zanini
