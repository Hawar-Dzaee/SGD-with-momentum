# SGD-with-momentum

Visualizing why SGD with momentum converges faster than Vanilla SGD

🛑 Please make sure to open the notebook in Google Colab for Plotly's graphs to render.

⚡ visualing the path and speed each optimization algorithm(SGD,SGD with momentum) will take given trained for 30 epochs.

Plotting (plain SGD) and (SGD with momentum) in the loss function landscape provides us with the intuition why SGD with momentum converges faster.
We are also aiming to show why overshooting when using SGD with momentum won't be a problem (in fact, it will help us escape local minima).



1- Loss(Cost) function Landscape with initial parameters, and Global minima. 
our task is to go(descent) from red point to the green point. 
![landscape](https://github.com/Hawar-Dzaee/SGD-with-momentum/assets/96496172/875c98fe-29d7-4936-88d7-be1b56722596)


2- Given 30 epochs, the loss function is not zero but we can see it's getting there. 
![vanilla_SGD](https://github.com/Hawar-Dzaee/SGD-with-momentum/assets/96496172/27f6d87d-aab7-43fa-a831-8e4018eaffa9)
