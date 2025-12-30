> Which parameters causes the mistake, how should I adjust them?

> The model works backwards by figuring out how much each parameter (weight/bias) contributed to the error and how much they need to change

The network calculates gradients which tell the following:
- Which direction should each parameter change to minimize [[Loss Function|loss]]? (increase/decrease)
- How much should it change?
- _Sort of like forces with magnitude & direction_