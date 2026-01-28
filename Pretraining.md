> Pretraining is the initial phase where a model learns broad patterns

> The model builds a foundational understanding

The model learns from a large general dataset before [[Fine Tuning|fine tuning]]

A model is only as good as the data it was trained on
#### Pretraining: [[Large Language Models|LLMs]]
LLMs are trained on **LARGE** amounts of text

Gathering data is much more complex than just scraping websites: Bad Input --> Bad Output

The model uses this data to adjust parameters ([[weights]] and [[biases]]) that modify how the model behaves/predicts

Parameters change how the models reacts to certain words, phrases, patterns, etc.
- All gathered text isn't stored in the Model
- Instead, the text is used to adjust these parameter values which capture general knowledge about the input text/language

> Just like when we learn how to play sports. We don't learn/memorize every single play we've ever seen. Instead, we "learn" movements, develop instincts, and habits that we use on a situational basis. In LLMs these "instincts" are the parameters

Number of parameters is often used as a measure of a model's power

Training the model is a loop that constantly adjusts the parameters to get the "best" output
- [[Neural Network#Training Process|Neural Network Training Process]]

