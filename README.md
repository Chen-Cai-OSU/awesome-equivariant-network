# awesome-equivariant-network
Paper list for equivariant neural network.

[toc]

### [Equivariance & Group convolution](#content)

1. **Group Equivariant Convolutional Networks**  
   *Taco S. Cohen, Max Welling* [paper](https://arxiv.org/pdf/1602.07576.pdf)
   Note: first paper; discrete group; 
   
2. **Learning SO(3) Equivariant Representations with Spherical CNNs** 
   *Carlos Esteves, Christine Allen-Blanchette, Ameesh Makadia, Kostas Daniilidis* ECCV 2018 [paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Carlos_Esteves_Learning_SO3_Equivariant_ECCV_2018_paper.html)
   Note: SO(3) equivariance; zonal filter

3. **Spherical CNNs**
	*Taco S. Cohen, Mario Geiger, Jonas Koehler, Max Welling* ICLR 2018 best paper  [paper](https://arxiv.org/abs/1801.10130)
	Note: use generalized FFT to speed up convolution on $S^2$ and $SO(3)$

4. **3D Steerable CNNs: Learning Rotationally Equivariant Features in Volumetric Data**
	*Maurice Weiler, Mario Geiger, Max Welling, Wouter Boomsma, Taco Cohen*  NeurIPS 2018 [paper](https://arxiv.org/abs/1807.02547)
	Note: SE(3) equivariance; characterize the basis of steerable kernel
	
5. **Tensor field networks: Rotation- and translation-equivariant neural networks for 3D point clouds**
*Nathaniel Thomas, Tess Smidt, Steven Kearnes, Lusann Yang, Li Li, Kai Kohlhoff, Patrick Riley* NeurIPS 2018 workshop: Molecules and Materials Workshop [paper](https://arxiv.org/abs/1802.08219)
Note: SE(3) equivariance for point clouds

6. **Gauge Equivariant Convolutional Networks and the Icosahedral CNN**
*Taco S. Cohen, Maurice Weiler, Berkay Kicanaoglu, Max Welling* ICML 2019 [paper](https://arxiv.org/abs/1902.04615)
Note: gauge equivariance on general manifold

7. **SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks**
  *Fabian B. Fuchs, Daniel E. Worrall, Volker Fischer, Max Welling* NeurIPS 2020  [paper](https://arxiv.org/abs/2006.10503)
Note: TFN + equivariant self-attention; improved spherical harmonics computation

8. **Gauge Equivariant Mesh CNNs: Anisotropic convolutions on geometric graphs**
*Pim de Haan, Maurice Weiler, Taco Cohen, Max Welling* ICLR 2021 [paper](https://arxiv.org/abs/2003.05425)
Note: anisotropic gauge equivariant kernels + message passing  by parallel transporting features over mesh edges

9. **Lorentz Group Equivariant Neural Network for Particle Physics**
*Alexander Bogatskiy, Brandon Anderson, Jan T. Offermann, Marwah Roussi, David W. Miller, Risi Kondor* ICML 2020 [paper](https://arxiv.org/abs/2006.04780)
Note: SO(1, 3) equivariance

10. **Generalizing Convolutional Neural Networks for Equivariance to Lie Groups on Arbitrary Continuous Data**
*Marc Finzi, Samuel Stanton, Pavel Izmailov, Andrew Gordon Wilson* ICML 2020 [paper](https://arxiv.org/abs/2002.12880)
Note: fairly generic architecture; use Monte Carlo sampling to achieve equivariance in expectation; 

11. **Spin-Weighted Spherical CNNs**
*Carlos Esteves, Ameesh Makadia, Kostas Daniilidis* NeurIPS 2020 [paper](https://arxiv.org/abs/2006.10731)
Note: anisotropic filter for vector field on sphere

### [Theory](#content)

1. **On the Universality of Rotation Equivariant Point Cloud Networks**
  *Nadav Dym, Haggai Maron* ICLR 2021 [paper](https://arxiv.org/abs/2010.02449)
  Note: universality for TFN and se3-transformer
2. **On the Generalization of Equivariance and Convolution in Neural Networks to the Action of Compact Groups**
Risi Kondor, Shubhendu Trivedi ICML 2018 [paper](https://arxiv.org/abs/1802.03690)
Note: convolution is all you need (for scalar fields)
3. **A General Theory of Equivariant CNNs on Homogeneous Spaces**
  *Taco Cohen, Mario Geiger, Maurice Weiler* NeurIPS 2019 [paper](https://arxiv.org/abs/1811.02017)
  Note: convolution is all you need (for general fields)
4. **Equivariance Through Parameter-Sharing**
  *Siamak Ravanbakhsh, Jeff Schneider, Barnabas Poczos* ICML 2017 [paper](https://arxiv.org/abs/1702.08389)
5. **Universal approximations of invariant maps by neural networks**
  Dmitry Yarotsky [paper](https://arxiv.org/abs/1804.10306)
6. **A Wigner-Eckart Theorem for Group Equivariant Convolution Kernels**
  Leon Lang, Maurice Weiler ICLR 2021 [paper](https://arxiv.org/abs/2010.10952)
  Note: steerable kernel spaces are fully understood and parameterized in terms of 1) generalized reduced matrix elements, 2) Clebsch-Gordan coefficients, and 3) harmonic basis functions on homogeneous spaces.

### [Application](#content)
1. **Trajectory Prediction using Equivariant Continuous Convolution**
*Robin Walters, Jinxi Li, Rose Yu* ICLR 2021 [paper](https://arxiv.org/abs/2010.11344)

2. **Incorporating Symmetry into Deep Dynamics Models for Improved Generalization**
  *Rui Wang, Robin Walters, Rose Yu* ICLR 2021 [paper](https://arxiv.org/abs/2002.03061)

3. **SE(3)-Equivariant Graph Neural Networks for Data-Efficient and Accurate Interatomic Potentials**
Simon Batzner, Tess E. Smidt, Lixin Sun, Jonathan P. Mailoa, Mordechai Kornbluth, Nicola Molinari, Boris Kozinsky [paper](https://arxiv.org/abs/2101.03164)

4. **Finding Symmetry Breaking Order Parameters with Euclidean Neural Networks**
Tess E. Smidt, Mario Geiger, Benjamin Kurt Miller [paper](https://arxiv.org/abs/2007.02005)

### [TODO](#content)
**Making Convolutional Networks Shift-Invariant Again** 
Richard Zhang ICML 2019 [paper](https://arxiv.org/abs/1904.11486)

