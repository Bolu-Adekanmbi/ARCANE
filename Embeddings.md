> Embeddings turn things(words/images/etc.) into points in space where things that are similar end up closer together and different things are far apart

> Embeddings allow us to take a medium (words/images/etc.) and map meaning to space

### LLM Context
Within the context of [[Large Language Models|LLMs]], embeddings allow us to map out semantic meaning of words

Similar words such as "walking", "walk", "walked" are close to each other

Words are mapped out to a high-dimensional space

Words are arranged in the dimensional space such that: 
If you subtract the vector of man from king and add the vector for woman, you get a result close to queen.
$$
\begin{aligned}
\vec{King} - \vec{Man} + \vec{Woman} \approx \vec{Queen} \\
\implies \vec{King} - \vec{Man} \approx \vec{Queen} - \vec{Woman} 
\end{aligned}
$$
