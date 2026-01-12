> Fine-tuning teaches a "generalized" AI to do a specific task better

> Further training the model on a high-quality dataset to improve performance in a specific task.

> [[Pretraining]] gives a model foundational knowledge, and then fine-tuning adjusts that knowledge to perform well within a specific domain

Fine Tuning adjusts model parameters to do a better job at a <u>specified</u> task

Fine tuning may also include making sure that the model is aligned to human values 
- This is rather interesting #TODO %%<-- I want to explore this more deeply %%

Typically, fine tuning involves using a smaller, high-quality dataset relevant to the specific task/domain.

Fine tuning requires updating the model weights. We makes changes to the model itself, **NOT** the model context/instructions.

Due to the scale of [[Foundation Model|foundation models]], fine-tuning models natively can be memory-intensive. Therefore, there are techniques for doing so with less memory. #TODO 