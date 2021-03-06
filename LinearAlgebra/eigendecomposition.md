$$
Av=\lambda v
$$

$$A$$是任意方阵。  
$$v$$是非零向量，是$$A$$的特征向量，通常只考虑单位特征向量
$$\lambda$$是$$A$$$的特征值

# 特征分解

$$
A = Vdiag(\lambda)V^-1
$$

所设A是一个n*n的方阵，则：
$$V$$是$$A$$的n个相互正交的特征向量连成的矩阵，即$$[v_1,v_2,...,v_n]$$
$$diag(\lambda)$$是特征向量对应的特征值形成的对角矩阵，即$$ \begin{bmatrix} \lambda_1 &  \\  & \lambda_2 \\ & & \ddots \\ & & & \lambda_n\\ \end{bmatrix}  $$  

对于任意的**实对称矩阵**A，有  
$$
A = Q\Lambda Q^T
$$
$$A$$是实对称矩阵。  
$$\Lambda$$是A的特征值降序排列形成的对角矩阵。  
$$Q$$是特征值对应的特征向量组成的正交矩阵。  

意义：将A看作是沿方向$$v^{(i)}$$延展i倍的空间（没看懂）

# 实对称矩阵特征分解的应用
优化二次方程：$$f(x)=x^TAx, \quad ||x||_2=1$$  
当x为A的某个特征向量时，f(x)为对应的特征值。  
$$f(x)_max$$为最大特征值。$$f(x)_min$$为最小特征值。  

