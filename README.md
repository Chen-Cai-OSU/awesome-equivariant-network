# awesome-equivariant-network
Paper list for equivariant neural network. Work-in-progress. 

Feel free to suggest relevant papers in the following format. 

```
	**Group Equivariant Convolutional Networks**  
   Taco S. Cohen, Max Welling ICML 2016 [paper](https://arxiv.org/pdf/1602.07576.pdf)   
```



[toc]

### [Equivariance & Group convolution](#content)

1. **Group Equivariant Convolutional Networks**  
   Taco S. Cohen, Max Welling ICML 2016 [paper](https://arxiv.org/pdf/1602.07576.pdf)   
   Note: first paper; discrete group; 
   
2. **Steerable CNNs**  
  Taco S. Cohen, Max Welling ICLR 2017 [paper](https://arxiv.org/abs/1612.08498)

3. **Harmonic Networks: Deep Translation and Rotation Equivariance**  
  Daniel E. Worrall, Stephan J. Garbin, Daniyar Turmukhambetov, Gabriel J. Brostow CVPR 2017 [paper](https://arxiv.org/abs/1612.04642)   
  
4. **Spherical CNNs**  
  Taco S. Cohen, Mario Geiger, Jonas Koehler, Max Welling ICLR 2018 best paper  [paper](https://arxiv.org/abs/1801.10130)  
  Note: use generalized FFT to speed up convolution on $S^2$ and $SO(3)$
  
5. **Clebsch–Gordan Nets: a Fully Fourier Space Spherical Convolutional Neural Network**  
  Risi Kondor, Zhen Lin, Shubhendu Trivedi NeurIPS 2018 [paper](https://arxiv.org/abs/1806.09231)  
  Note: perform equivariant nonlinearity in Fourier space; 

6. **General E(2)-Equivariant Steerable CNNs**  
  Maurice Weiler, Gabriele Cesa NeurIPS 2019 [paper](https://arxiv.org/abs/1911.08251)  
  Note: nice benchmark on different reprsentations
  
7. **Learning SO(3) Equivariant Representations with Spherical CNNs**  
   Carlos Esteves, Christine Allen-Blanchette, Ameesh Makadia, Kostas Daniilidis ECCV 2018 [paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Carlos_Esteves_Learning_SO3_Equivariant_ECCV_2018_paper.html)  
Note: SO(3) equivariance; zonal filter
   
8. **3D Steerable CNNs: Learning Rotationally Equivariant Features in Volumetric Data**  
  Maurice Weiler, Mario Geiger, Max Welling, Wouter Boomsma, Taco Cohen  NeurIPS 2018 [paper](https://arxiv.org/abs/1807.02547)  
  Note: SE(3) equivariance; characterize the basis of steerable kernel
  
9. **Tensor field networks: Rotation- and translation-equivariant neural networks for 3D point clouds**  
  Nathaniel Thomas, Tess Smidt, Steven Kearnes, Lusann Yang, Li Li, Kai Kohlhoff, Patrick Riley  [paper](https://arxiv.org/abs/1802.08219)  
  Note: SE(3) equivariance for point clouds
  
10. **Gauge Equivariant Convolutional Networks and the Icosahedral CNN**  
  Taco S. Cohen, Maurice Weiler, Berkay Kicanaoglu, Max Welling ICML 2019 [paper](https://arxiv.org/abs/1902.04615)  
  Note: gauge equivariance on general manifold
  
11. **Cormorant: Covariant Molecular Neural Networks**  
   Brandon Anderson, Truong-Son Hy, Risi Kondor NeurIPS 2019 [paper](https://arxiv.org/abs/1906.04015)

12. **Deep Scale-spaces: Equivariance Over Scale**  
   Daniel Worrall, Max Welling NeurIPS 2019 [paper](https://papers.nips.cc/paper/2019/hash/f04cd7399b2b0128970efb6d20b5c551-Abstract.html)

13. **SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks**  
   Fabian B. Fuchs, Daniel E. Worrall, Volker Fischer, Max Welling NeurIPS 2020  [paper](https://arxiv.org/abs/2006.10503), [blog](https://fabianfuchsml.github.io/se3transformer/)  
   Note: TFN + equivariant self-attention; improved spherical harmonics computation
   
14. **Gauge Equivariant Mesh CNNs: Anisotropic convolutions on geometric graphs**  
   Pim de Haan, Maurice Weiler, Taco Cohen, Max Welling ICLR 2021 [paper](https://arxiv.org/abs/2003.05425)  
   Note: anisotropic gauge equivariant kernels + message passing  by parallel transporting features over mesh edges
   
15. **Lorentz Group Equivariant Neural Network for Particle Physics**  
   Alexander Bogatskiy, Brandon Anderson, Jan T. Offermann, Marwah Roussi, David W. Miller, Risi Kondor ICML 2020 [paper](https://arxiv.org/abs/2006.04780)  
   Note: SO(1, 3) equivariance
   
16. **Generalizing Convolutional Neural Networks for Equivariance to Lie Groups on Arbitrary Continuous Data**  
   Marc Finzi, Samuel Stanton, Pavel Izmailov, Andrew Gordon Wilson ICML 2020 [paper](https://arxiv.org/abs/2002.12880)  
   Note: fairly generic architecture; use Monte Carlo sampling to achieve equivariance in expectation; 
   
17. **Spin-Weighted Spherical CNNs**  
   Carlos Esteves, Ameesh Makadia, Kostas Daniilidis NeurIPS 2020 [paper](https://arxiv.org/abs/2006.10731)  
   Note: anisotropic filter for vector field on sphere
   
18. **Learning Invariances in Neural Networks**  
   Gregory Benton, Marc Finzi, Pavel Izmailov, Andrew Gordon Wilson NeurIPS 2020 [paper](https://arxiv.org/abs/2010.11882)   
   Note: very interesting approch; enfore "soft" invariance via learning over both model parameters and distributions over augmentations

19. **Lie Algebra Convolutional Neural Networks with Automatic Symmetry Extraction**  
   Nima Dehmamy, Yanchen Liu, Robin Walters, Rose Yu  [paper](https://openreview.net/forum?id=cTQnZPLIohy)    
   Note: very interesting paper; It’s unfortunate that it is rejected by ICLR 2021  

20. **LieTransformer: Equivariant self-attention for Lie Groups**  
   Michael Hutchinson, Charline Le Lan, Sheheryar Zaidi, Emilien Dupont, Yee Whye Teh, Hyunjik Kim [paper](https://arxiv.org/abs/2012.10885)  
   Note: equivariant self attention to arbitrary Lie groups and their discrete subgroups

### [Theory](#content)

1. **On the Generalization of Equivariance and Convolution in Neural Networks to the Action of Compact Groups**  
  Risi Kondor, Shubhendu Trivedi ICML 2018 [paper](https://arxiv.org/abs/1802.03690)  
  Note: convolution is all you need (for scalar fields)
  
3. **A General Theory of Equivariant CNNs on Homogeneous Spaces**  
  Taco Cohen, Mario Geiger, Maurice Weiler NeurIPS 2019 [paper](https://arxiv.org/abs/1811.02017)  
  Note: convolution is all you need (for general fields)
  
4. **Equivariance Through Parameter-Sharing**  
  Siamak Ravanbakhsh, Jeff Schneider, Barnabas Poczos ICML 2017 [paper](https://arxiv.org/abs/1702.08389)
  
5. **Universal approximations of invariant maps by neural networks**  
  Dmitry Yarotsky [paper](https://arxiv.org/abs/1804.10306)
  
6. **A Wigner-Eckart Theorem for Group Equivariant Convolution Kernels**  
  Leon Lang, Maurice Weiler ICLR 2021 [paper](https://arxiv.org/abs/2010.10952)  
  Note: steerable kernel spaces are fully understood and parameterized in terms of 1) generalized reduced matrix elements, 2) Clebsch-Gordan coefficients, and 3) harmonic basis functions on homogeneous spaces.
  
7. **On the Universality of Rotation Equivariant Point Cloud Networks**  
  Nadav Dym, Haggai Maron ICLR 2021 [paper](https://arxiv.org/abs/2010.02449),   
  Note: universality for TFN and se3-transformer 
  
8.   **Universal Equivariant Multilayer Perceptrons**  
Siamak Ravanbakhsh [paper](https://arxiv.org/abs/2002.02912)

### [Application](#content)
1. **Trajectory Prediction using Equivariant Continuous Convolution**  
  Robin Walters, Jinxi Li, Rose Yu ICLR 2021 [paper](https://arxiv.org/abs/2010.11344)
2. **Incorporating Symmetry into Deep Dynamics Models for Improved Generalization**  
  Rui Wang, Robin Walters, Rose Yu ICLR 2021 [paper](https://arxiv.org/abs/2002.03061)
3. **SE(3)-Equivariant Graph Neural Networks for Data-Efficient and Accurate Interatomic Potentials**  
  Simon Batzner, Tess E. Smidt, Lixin Sun, Jonathan P. Mailoa, Mordechai Kornbluth, Nicola Molinari, Boris Kozinsky [paper](https://arxiv.org/abs/2101.03164)
4. **Finding Symmetry Breaking Order Parameters with Euclidean Neural Networks**  
  Tess E. Smidt, Mario Geiger, Benjamin Kurt Miller [paper](https://arxiv.org/abs/2007.02005)
5. **Group Equivariant Generative Adversarial Networks**  
Neel Dey, Antong Chen, Soheil Ghafurian ICLR 2021  [paper](https://arxiv.org/abs/2005.01683)   
7. **Ab-Initio Solution of the Many-Electron Schrödinger Equation with Deep Neural Networks**  
David Pfau, James S. Spencer, Alexander G. de G. Matthews, W. M. C. Foulkes [paper](https://arxiv.org/abs/1909.02487)  

### [Permutation Equivariance](#content)

There are many paper on this topics. I only added very few of them.

1. **PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation**  
  Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas CVPR 2017 [paper](https://arxiv.org/abs/1612.00593) 
2. **Deep Sets**  
Manzil Zaheer, Satwik Kottur, Siamak Ravanbakhsh, Barnabas Poczos, Ruslan Salakhutdinov, Alexander Smola NeurIPS 2017   [paper](https://arxiv.org/abs/1703.06114)
3. **Invariant and Equivariant Graph Networks**  
  Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman ICLR 2019 [paper](https://arxiv.org/abs/1812.09902)  
4. **Provably Powerful Graph Networks**  
  Haggai Maron, Heli Ben-Hamu, Hadar Serviansky, Yaron Lipman NeurIPS 2019 [paper](https://arxiv.org/abs/1905.11136)  
5. **Universal Invariant and Equivariant Graph Neural Networks**  
  Nicolas Keriven, Gabriel Peyré NeurIPS 2019 [paper](https://papers.nips.cc/paper/2019/hash/ea9268cb43f55d1d12380fb6ea5bf572-Abstract.html)
6. **On Learning Sets of Symmetric Elements**  
  Haggai Maron, Or Litany, Gal Chechik, Ethan Fetaya [ICML 2020 best paper](https://arxiv.org/abs/2002.08599)
7. **On the Universality of Invariant Networks**  
  Haggai Maron, Ethan Fetaya, Nimrod Segol, Yaron Lipman [paper](https://arxiv.org/abs/1901.09342)


### [Talk & Tutorial](#content)

IAS: [Graph Nets: The Next Generation - Max Welling - YouTube](https://www.youtube.com/watch?v=Wx8J-Kw3fTA&t=3602s)

[Equivariance and Data Augmentation workshop](https://sites.google.com/view/equiv-data-aug/home): many nice talks

IPAM: [Tess Smidt: "Euclidean Neural Networks for Emulating Ab Initio Calculations and Generating Atomi..." - YouTube](https://www.youtube.com/watch?v=8CF8Grb_brE)

IPAM: [E(3) Equivariant Neural Network Tutorial ](https://blondegeek.github.io/e3nn_tutorial/)

IPAM: [Risi Kondor: "Fourier space neural networks" ](https://www.youtube.com/watch?v=-PVyi0Keiec)

[NeurIPS 2020 tutorial: Equivariant Networks](https://nips.cc/virtual/2020/public/tutorial_3e267ff3c8b6621e5ad4d0f26142892b.html)


### [TO READ](#content)
There are many paper I haven't read carefully yet. 

1. **Making Convolutional Networks Shift-Invariant Again**   
  Richard Zhang ICML 2019 [paper](https://arxiv.org/abs/1904.11486)
2. **Probabilistic symmetries and invariant neural networks**  
Benjamin Bloem-Reddy, Yee Whye Teh JMLR [paper](https://arxiv.org/abs/1901.06082)
3. **On Representing (Anti)Symmetric Functions**  
Marcus Hutter [paper](https://arxiv.org/abs/2007.15298)
