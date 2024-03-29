The value function candidate:
For the set $S: \{X \in \mathbb{R}^2| X^T X \geq 4\}$ and for all $X \in S$, $u \in [0,u_{max}]$, a value function satisfies $V(X) \geq 0$ and $\dot{V}(X) \leq 0$ is the following:\
$V = 4.1546\cdot 10^{-8} x^6 - 3.3917\cdot 10^{-11} x^5 x_c + 4.1488\cdot 10^{-8} x^4 x_c^2 + 5.5977 \cdot 10^{-13} x^3x_c^3$
$+ 4.1487\cdot 10^{-8} x^2 x_c^4 + 6.4159\cdot 10^{-14} x x_c^5 + 4.1503\cdot 10^{-8} x_c^6$
$- 5.8769\cdot 10^{-10} x^5 + 4.6531\cdot 10^{-10} x^4 x_c - 1.3295\cdot 10^{-11} x^3 x_c^2 $
$- 1.8008\cdot 10^{-12} x^2 x_c^3 - 1.627\cdot 10^{-13} x x_c^4 + 1.1371\cdot 10^{-13} x_c^5 + 4.7693\cdot 10^{-8} x^4 $
$- 5.3418\cdot 10^{-9} x^3 x_c + 4.0518\cdot 10^{-8} x^2 x_c^2 + 5.2205\cdot 10^{-12} x x_c^3 + 4.1185\cdot 10^{-8} x_c^4 - 5.1859\cdot 10^{-8} x^3 + 4.7322\cdot 10^{-8} x^2 x_c$
$- 2.3148\cdot 10^{-10} x x_c^2 - 2.0213\cdot 10^{-11} x_c^3$
$+ 2.6092\cdot 10^{-7} x^2 - 2.829 \cdot 10^{-7} x x_c + 2.7901\cdot 10^{-8} x_c^2 $
$- 5.412\cdot 10^{-11} x + 8.4943\cdot 10^{-7} x_c + 4.1841$.

The formatting of the statisitics in spreadsheet is as follows:
Columns 1,2 represent the initial conditions $(T_0,T_{lag})$. Column 3 represents which data set the feedback control uses. 'TO' represents that the data are from time-optimal entrainment data and 'QC' represents that the data are from MCQC data. Columns 4 - 6 represent the mean of cumulative quadratic costs $J$, the variance of $J$, and whether the difference in J between time-optimal feedback and quadratic cost feedback passes 5% significance level paired-sample t-test. 'Y' stands for there is a significant difference between 'TO' and 'QC' data and 'N' stands for there is no significant difference between 'TO' and 'QC' data. Columns 7 - 9 are the mean of time taken to reach error threshold $\epsilon = 0.01$: $T_{\epsilon}$, the variance of time $T_{\epsilon}$, and whether the difference in J between time-optimal feedback and quadratic cost feedback passes 5% significance level paired t-test. 'Y' stands for there is a significant difference between 'TO' and 'QC' data and 'N' stands for there is no significant difference between 'TO' and 'QC' data. The bold numbers stand for the better one between 'TO' and 'QC'.
