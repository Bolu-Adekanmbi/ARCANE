> The process of chopping up sentences into bite-sized pieces

### Steps
1. Break down text into smaller units called <u>tokens</u>
2. Each Token --mapped--> Numerical value
	- A numerical value that the model can process
3. Models learn to understand statistical relationship between tokens

Once a model is able to understand relationships between tokens, in the context of [[Large Language Models|LLMs]], the next object is to apply this understanding by predicting the next token given a series of token inputs

### Tokenization Techniques
1. Subword tokenization
	- [[Byte Pair Encoding|Byte Pair Encoding (BPE)]] #TODO 

There are specialized [[Tokenizers|tokenizers]] for processing math and code! #TODO  

### Token?
Basic unit of a language model

Tokens can be a character, a word, or just a part of a word (e.g. -tion)

Why Tokens and Not words?
- Ability to break down words into meaningful components: e.g. “cooking” can be broken into “cook” and “ing” with both parts having their own definitions that build upon each other.
- Fewer unique tokens than unique words. Reduces model [[Vocabulary|vocabulary]] size, making it more efficient
- Tokens help a model process unseen new words. E.g. a made up term “chatgpting” can still be understood by a model based on the understanding of “chagpt” and “ing”.

Tokens: Less units than words + more meaning than individual characters

