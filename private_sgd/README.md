# Programming Exercise: DP-SGD

This programming exercise is dedicated to the DP version of \emph{Stochastic Gradient Descent}: \emph{DP-SGD}. 

Complete the code by filling in the TODOs:
- Implement the \emph{clip\_(...)} function that applies the norm clipping. 
- Implement the addition of adequately scaled noise to the gradient that is used to update the network's parameters. 

If successful, the training should succeed\footnote{Training takes about 1-2 minutes per epoch. Both accuracies should end up well above 90\% after training. Afterward, you should see plots of the training accuracy and loss progression.