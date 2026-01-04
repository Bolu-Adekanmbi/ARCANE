> Model teaches itself without human-made labels. It creates its own labels.

Self-supervised learning overcomes the [[Data Labeling|data labeling]] bottleneck

The model infers labels from the input data.

### [[Language Model]] Context
With language models, each input sequence self-contains a combination of input (context) and output (next token). 

The sentence: “I love eating chocolate” can be broken into various combinations of input and output:

| Input                | Output    |
| -------------------- | --------- |
| BOS                  | `I`       |
| BOS, I               | love      |
| BOS, I, love         | eating    |
| BOS, I, love, eating | chocolate |
> BOS/EOS: Beginning/End of Sequence <— each sequence marker is treated as a token

With self-supervised, [[Language Model|language models]] don’t require labeling. Text sequences are everywhere: books, comments online, etc. 

This makes it possible to gather a large amount of training data, allowing [[Language Model|language models]] to scale to become [[Large Language Models|LLMs]]