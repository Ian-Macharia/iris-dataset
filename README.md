# iris-dataset
Prediciting the class of the iris flower based on available attributes, using the classic iris dataset.

To find out:
I was curious to see whether encoding the dependent variable would have any effect on the outcome of a logistic regression after seeing a notebook where the dependent variable had been encoded before the regression was run. 
I ran the solution both with and without the explicit encoding of the target variable. There was no effect on the overall equation, this is because sckit-learn implicitly encodes the dependent varible by default.
