## Overview
Explored 3 extractive, 2 abstractive approaches and an approach focusing on a mix of both, for news article summarization on ILSUM 2022 dataset [https://ilsum.github.io/ilsum/2022/dataset.html]

## Extractive Approaches
• Extracting the sentence which has highest rouge score with the document
• Extracting top 10% sentences which have highest rouge score with the document
• Bert extractive summarization 

## Abstractive Approaches
• T5-small
• T5 fine tuned on news dataset

## Extractive + Abstractive Approach
• Filtering redundant informative content using Dynamic Mode Decomposition followed by summarization by an abstractive model
