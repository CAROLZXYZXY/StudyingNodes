# Introduction
## Definition
f : X -> Y (f is more powerful), X,Y could be sequence, trees, discrete labels, etc.  

## Unified Framework
Find a function F: X * Y -> R  
F(X, Y) evaluate how compatible the object x and y is  
f(X) = argmax F(X,Y) (list all the Y)  

## Statistics View
Training: P(X,Y) -> [0, 1]   
Inference: argmax P(y|x) = argmax P(x, y)   
Drawback for probability: 0-1 constraint is not necessary  
Strength for probability: meaningful  

## Three problems
1. What does F(x, y) look like  
2. How to solve argmax (B&B, Viterbi, etc)  
3. How to find F(x, y)    

# Structured Linear Model
F(x, y) is a linear combination of characteristics
F(x, y) = w * phi(x, y)  
w is learned from training data, Perceptron Alg.  
(Binary classification is a special case of Structured Learning)  
But, assumption is that all the characteristics are separable. (We may rely on Structured SVM)

# Structured SVM   
