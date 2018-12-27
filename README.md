# Logistic-Regression-Regresion-Logistica
A simple implementation of algorithms of logistic regression  using Numpy, Scipy, pandas.
#### Cost function: 

<a href="https://www.codecogs.com/eqnedit.php?latex=J(\theta)=\frac{1}{m}\sum_{i&space;=&space;1}^m&space;[-y^{(i)}log(h_\theta(x^{(i)}))-(1-y^{(i)})log(1-h_\theta(x^{(i)}))]" target="_blank"><img src="https://latex.codecogs.com/gif.latex?J(\theta)=\frac{1}{m}\sum_{i&space;=&space;1}^m&space;[-y^{(i)}log(h_\theta(x^{(i)}))-(1-y^{(i)})log(1-h_\theta(x^{(i)}))]" title="J(\theta)=\frac{1}{m}\sum_{i = 1}^m [-y^{(i)}log(h_\theta(x^{(i)}))-(1-y^{(i)})log(1-h_\theta(x^{(i)}))]" /></a>

where : 

<a href="https://www.codecogs.com/eqnedit.php?latex=h_\theta(x)=\frac{1}{1&plus;e^-\theta^{T_x}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?h_\theta(x)=\frac{1}{1&plus;e^-\theta^{T_x}}" title="h_\theta(x)=\frac{1}{1+e^-\theta^{T_x}}" /></a>

#### Gradient: 

<a href="https://www.codecogs.com/eqnedit.php?latex=\frac{\partial&space;J(\theta)}{\partial&space;\theta_j}&space;=\frac{1}{m}\sum_{i&space;=&space;1}^m&space;(H_\theta(x^{(i)})-y^{(i)})x_j^{(i)}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\frac{\partial&space;J(\theta)}{\partial&space;\theta_j}&space;=\frac{1}{m}\sum_{i&space;=&space;1}^m&space;(H_\theta(x^{(i)})-y^{(i)})x_j^{(i)}" title="\frac{\partial J(\theta)}{\partial \theta_j} =\frac{1}{m}\sum_{i = 1}^m (H_\theta(x^{(i)})-y^{(i)})x_j^{(i)}" /></a>
