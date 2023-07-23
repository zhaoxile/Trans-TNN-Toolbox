# Transformed TNN Toolbox (Matlab)

Ben-Zheng Li, Yu-Bang Zheng, Tai-Xiang Jiang, Xi-Le Zhao

## 1. Introduction

The transformed tensor singular values decomposition (t-SVD) captures the low-rankness of the frontal slices under the given transform, which mitigates the inherent information loss to matricization or tensor flattening. We develop a TranTSVD toolbox in Matlab with the tensor completion task as an example. The TranTSVD toolbox includes the classical transformed t-SVD methods \cite{Jiang}, such as the standrad DFT-based TNN, the unitary transformed TNN (UTNN), the framelet transformed TNN (FTNN), and the nonlinear transformed TNN (NTTNN). Table \ref{tnn} lists the used functions in the TranTSVD toolbox.

## 2. Example

Simply run the “Demo.m” to test all the transformed tensor nuclear norm methods.

## 3. Citation

Please cite the corresponding references when using the TenNet toolbox in your papers.

[1] T.-X. Jiang, M. K. Ng, and X.-L. Zhao, “Chapter 2: Transform-based tensor singular value decomposition in multidimensional image recovery,” in Tensors for Data Processing, Y. Liu, Ed. Academic Press, 2022, pp. 31–60.

[2] M. E. Kilmer and C. D. Martin, “Factorization strategies for third-order tensors,” Linear Algebra and its Applications, vol. 435, no. 3, pp. 641–658, 2011.

[3] C. Lu, J. Feng, Y. Chen, W. Liu, Z. Lin, and S. Yan, “Tensor robust principal component analysis with a new tensor nuclear norm,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 42, no. 4, pp. 925–938, 2020.

[4] G.-J. Song, M. K. Ng, and X.-J. Zhang, “Robust tensor completion using transformed tensor singular value decomposition,” Numerical Linear Algebra with Applications, vol. 27, p. e2299, 2020.

[5] T.-X. Jiang, M. K. Ng, X.-L. Zhao, and T.-Z. Huang, “Framelet representation of tensor nuclear norm for third-order tensor completion,” IEEE Transactions on
Image Processing, vol. 29, pp. 7233–7244, 2020.

[6] B.-Z. Li, X.-L. Zhao, T.-Y. Ji, X.-J. Zhang, and T.-Z. Huang, “Nonlinear transform induced tensor nuclear norm for tensor completion,” Journal of Scientific
Computing, vol. 92, 2022.
