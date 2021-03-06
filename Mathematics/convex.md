**凸优化问题**是指约束最优化问题：  
$$
\begin{aligned}
min_w f(w)  \\
s.t. g_i(w) \le 0, i = 1,2,\cdots,k   \\
h_i(w) = 0, i = 1,2,\cdots,l
\end{aligned}
$$

其中，  
目标函数f(w)和约束函数g(w)都是Rn上连续可微的凸函数。    
约束函数h(w)是Rn上的仿射函数。  

**凸二次规划问题**：当目标函数f(w)是二次函数且约束函数g(w)是仿射函数时，上述凸优化问题成为凸二次规划问题。  

**强凸问题**：
$$
f(y) \ge f(x) + \nabla f(x)^\top(y-x) + \frac{\mu}{2}||y-x||
$$