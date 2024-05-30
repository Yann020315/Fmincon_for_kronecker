# Fmincon_for_kronecker

Given $T_1$:=$ (x_1x_1^{T}) \bigotimes (x_2x_2^{T}) \bigotimes (x_3x_3^{T}) \in \mathbb{R}^{1000x1000}$, where\\ 
$x_i$ are vectors with 10 dimensions of norm 1.\\
The problem becomes f(x)= $\Vert T_1 -  (\hat{x_1}\hat{x_1}^{T}) \bigotimes (\hat{x_2}\hat{x_2}^{T}) \bigotimes (\hat{x_3}\hat{x_3}^{T})\Vert_F$
