> Making slight changes to the model to reduce loss and get a better output

Using the gradients from [[Backpropagation|backpropagation]], the model updates parameters to reduce [[Loss Function|loss]]

This repeats many times:
1. Make a prediction
2. Measure the error
3. Adjust the parameter 
	- This is typically done based on a set [[Learning rate|learning rate]]
4. Try again