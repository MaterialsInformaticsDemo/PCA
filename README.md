

**Case 1: PCA on Original Features**

Input features:
- \( x_1 = [8.895, 8.960, 8.630, 9.500, 8.370] \)
- \( x_2 = [40, 40, 110, 100, 505] \)

Covariance matrix after centering:
\[
\begin{bmatrix}
1.783050 \times 10^{-1} & -5.302375 \times 10^{1} \\
-5.302375 \times 10^{1} & 3.848000 \times 10^{4}
\end{bmatrix}
\]

PCA vectors:
\[
\begin{bmatrix}
-0.00137796 & 0.99999905 \\
0.99999905 & 0.00137796
\end{bmatrix}
\]

PCA variances:
\[
[3.84800731 \times 10^{4}, 1.05240401 \times 10^{-1}]
\]

**Case 2: PCA on Standardized Features**

Covariance matrix after centering:
\[
\begin{bmatrix}
1.783050 \times 10^{-1} & -5.302375 \times 10^{1} \\
-5.302375 \times 10^{1} & 3.848000 \times 10^{4}
\end{bmatrix}
\]

PCA vectors:
\[
\begin{bmatrix}
-0.00137796 & 0.99999905 \\
0.99999905 & 0.00137796
\end{bmatrix}
\]

PCA variances:
\[
[3.84800731 \times 10^{4}, 1.05240401 \times 10^{-1}]
\]

**Case 3: PCA on Normalized and Centered Features**

Covariance matrix after normalization and centering:
\[
\begin{bmatrix}
0.13963897 & -0.10091112 \\
-0.10091112 & 0.17796277
\end{bmatrix}
\]

PCA vectors:
\[
\begin{bmatrix}
-0.63774788 & -0.77024518 \\
0.77024518 & -0.63774788
\end{bmatrix}
\]

PCA variances:
\[
[0.26151520, 0.05608654]
\]

**Case 4: PCA on Centered and Scaled Features**

Covariance matrix after centering and scaling:
\[
\begin{bmatrix}
0.45067372 & -0.24363725 \\
-0.24363725 & 0.32142738
\end{bmatrix}
\]

PCA vectors:
\[
\begin{bmatrix}
-0.60976305 & -0.79258376 \\
-0.79258376 & 0.60976305
\end{bmatrix}
\]

PCA variances:
\[
[0.13398852, 0.63811257]
\]

