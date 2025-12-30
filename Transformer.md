> Transformer models are able to *learn* **CONTEXT**

> Transformer architecture allows models to understand how words relate to each other in a sequence

Transformers use a mathematical technique called [[self-attention]] to detect subtle ways in which elements in a sequence relate to each other
- This enables understanding of ...
	- ...how the end of a sentence connects to the beginning
	- ...how a starting word connects to the words that follow
	- ...how paragraphs connect with one another

Transformer architecture on some level <u>understand</u> **semantics**

Transformers were introduced in the paper: [[Attention Is All You Need]]

%%### Technical Know-how%%

In Transformer Architecture words are converted to [[Embeddings|embeddings]]

Transformers can consider the _ENTIRE_ input sequence at once, allowing it to understand a word (e.g. "it") by considering the context of the sentence/paragraph