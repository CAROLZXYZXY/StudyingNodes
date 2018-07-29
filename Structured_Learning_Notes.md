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
2. How to solve argmax  
3. How to find F(x, y)    

# Structured Linear Model
$$ F(X,Y)$$
