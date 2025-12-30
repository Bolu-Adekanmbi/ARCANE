---
aliases:
  - RL
---

> RL is the process of learning by trial and error with rewards and punishments (penalties)

> The model gives an output, checks to see what it rewards/punishment it gets, and then tries to increase its next reward while avoiding penalties

> RL is about rewarding good behavior instead of directly giving the answer

#### RLHF (Reinforcement Learning From Human Feedback)
[[Large Language Models|LLM]] Context:
1. [[Artificial Intelligence|AI]] Model generates several potential responses for a given input
2. Human reviewers rank these responses on a set criteria based on accuracy, helpfulness, etc.
3. Based on the rankings, a separate model called a [[Reward Model]] is trained to predict the quality of responses
4. The original AI model is then [[Fine Tuning|fine tuned]] using reinforcement learning techniques guided by the [[Reward Model|reward model]]