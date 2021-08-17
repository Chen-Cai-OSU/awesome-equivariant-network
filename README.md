# awesome-equivariant-network

Paper list for equivariant neural network. Work-in-progress. 

Feel free to suggest relevant papers in the following format. 

```markdown
**Group Equivariant Convolutional Networks**  
Taco S. Cohen, Max Welling ICML 2016 [paper](https://arxiv.org/pdf/1602.07576.pdf)   
```

*Acknowledgement*: I would like to thank Maurice Weiler, Fabian Fuchs, Tess Smidt, Rui Wang, David Pfau, Jonas Köhler, Taco Cohen, Gregor Simm, Erik J Bekkers, Jean-Baptiste Cordonnier, David W. Romero, Ivan Sosnovik, Kostas Daniilidis for paper suggestions! Thank Weihao Xia for helping out typesetting! 

### Table of Contents
- [Equivariance and Group convolution](#equivariance-and-Group-convolution)
- [Theory](#theory)
- [Equivariant Density Estimation and Sampling](equivariant-density-estimation-and-sampling)
- [Application](#application)
- [Permutation Equivariance](#permutation-equivariance)
- [Talk and Tutorial](#talk-and-tutorial)
- [TO READ](#to-read)

### [Equivariance and Group convolution](#content)

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
  
7. **Learning Steerable Filters for Rotation Equivariant CNNs**  
   Maurice Weiler, Fred A. Hamprecht, Martin Storath CVPR 2018 [paper](https://arxiv.org/abs/1711.07289)   
   Note: group convolutions, kernels parameterized in circular harmonic basis (steerable filters);
   
8. **Learning SO(3) Equivariant Representations with Spherical CNNs**  
   Carlos Esteves, Christine Allen-Blanchette, Ameesh Makadia, Kostas Daniilidis ECCV 2018 [paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Carlos_Esteves_Learning_SO3_Equivariant_ECCV_2018_paper.html)  
   Note: SO(3) equivariance; zonal filter
   
9. **Polar Transformer Networks**  
  Carlos Esteves, Christine Allen-Blanchette, Xiaowei Zhou, Kostas Daniilidis ICLR 2018 [paper](https://arxiv.org/abs/1709.01889)  

10. **3D Steerable CNNs: Learning Rotationally Equivariant Features in Volumetric Data**  
  Maurice Weiler, Mario Geiger, Max Welling, Wouter Boomsma, Taco Cohen  NeurIPS 2018 [paper](https://arxiv.org/abs/1807.02547)  
  Note: SE(3) equivariance; characterize the basis of steerable kernel
  
11. **Tensor field networks: Rotation- and translation-equivariant neural networks for 3D point clouds**  
   Nathaniel Thomas, Tess Smidt, Steven Kearnes, Lusann Yang, Li Li, Kai Kohlhoff, Patrick Riley  [paper](https://arxiv.org/abs/1802.08219)  
   Note: SE(3) equivariance for point clouds
   
12. **Equivariant Multi-View Networks**  
   Carlos Esteves, Yinshuang Xu, Christine Allen-Blanchette, Kostas Daniilidis  ICCV 2019 [paper](https://arxiv.org/abs/1904.00993)   
   
13. **Gauge Equivariant Convolutional Networks and the Icosahedral CNN**  
   Taco S. Cohen, Maurice Weiler, Berkay Kicanaoglu, Max Welling ICML 2019 [paper](https://arxiv.org/abs/1902.04615), [talk](https://slideslive.com/38915809/gauge-equivariant-convolutional-networks?locale=de)  
   Note: gauge equivariance on general manifold
   
14. **Cormorant: Covariant Molecular Neural Networks**  
   Brandon Anderson, Truong-Son Hy, Risi Kondor NeurIPS 2019 [paper](https://arxiv.org/abs/1906.04015)
   
15. **Deep Scale-spaces: Equivariance Over Scale**  
   Daniel Worrall, Max Welling NeurIPS 2019 [paper](https://papers.nips.cc/paper/2019/hash/f04cd7399b2b0128970efb6d20b5c551-Abstract.html)
   
16. **Scale-Equivariant Steerable Networks**  
   Ivan Sosnovik, Michał Szmaja, Arnold Smeulders ICLR 2020 [paper](https://openreview.net/forum?id=HJgpugrKPS)
   
17. **B-Spline CNNs on Lie Groups**  
   Erik J Bekkers ICLR 2020 [paper](https://openreview.net/forum?id=H1gBhkBFDH)    
   
18. **SE(3)-Transformers: 3D Roto-Translation Equivariant Attention Networks**  
   Fabian B. Fuchs, Daniel E. Worrall, Volker Fischer, Max Welling NeurIPS 2020  [paper](https://arxiv.org/abs/2006.10503), [blog](https://fabianfuchsml.github.io/se3transformer/)  
   Note: TFN + equivariant self-attention; improved spherical harmonics computation
   
19. **Gauge Equivariant Mesh CNNs: Anisotropic convolutions on geometric graphs**  
   Pim de Haan, Maurice Weiler, Taco Cohen, Max Welling ICLR 2021 [paper](https://arxiv.org/abs/2003.05425)  
   Note: anisotropic gauge equivariant kernels + message passing  by parallel transporting features over mesh edges
   
20. **Lorentz Group Equivariant Neural Network for Particle Physics**  
   Alexander Bogatskiy, Brandon Anderson, Jan T. Offermann, Marwah Roussi, David W. Miller, Risi Kondor ICML 2020 [paper](https://arxiv.org/abs/2006.04780)  
   Note: SO(1, 3) equivariance
   
21. **Generalizing Convolutional Neural Networks for Equivariance to Lie Groups on Arbitrary Continuous Data**  
   Marc Finzi, Samuel Stanton, Pavel Izmailov, Andrew Gordon Wilson ICML 2020 [paper](https://arxiv.org/abs/2002.12880)  
   Note: fairly generic architecture; use Monte Carlo sampling to achieve equivariance in expectation; 
   
22. **Spin-Weighted Spherical CNNs**  
   Carlos Esteves, Ameesh Makadia, Kostas Daniilidis NeurIPS 2020 [paper](https://arxiv.org/abs/2006.10731)  
   Note: anisotropic filter for vector field on sphere
   
23. **Learning Invariances in Neural Networks**  
   Gregory Benton, Marc Finzi, Pavel Izmailov, Andrew Gordon Wilson NeurIPS 2020 [paper](https://arxiv.org/abs/2010.11882)   
   Note: very interesting approch; enfore "soft" invariance via learning over both model parameters and distributions over augmentations
   
24. **Lie Algebra Convolutional Neural Networks with Automatic Symmetry Extraction**  
   Nima Dehmamy, Yanchen Liu, Robin Walters, Rose Yu  [paper](https://openreview.net/forum?id=cTQnZPLIohy)    
   Note: very interesting paper; It’s unfortunate that it is rejected by ICLR 2021  
   
25. **LieTransformer: Equivariant self-attention for Lie Groups**  
   Michael Hutchinson, Charline Le Lan, Sheheryar Zaidi, Emilien Dupont, Yee Whye Teh, Hyunjik Kim [paper](https://arxiv.org/abs/2012.10885)  
   Note: equivariant self attention to arbitrary Lie groups and their discrete subgroups
   
26. **Co-Attentive Equivariant Neural Networks: Focusing Equivariance On Transformations Co-Occurring In Data**  
   David W. Romero, Mark Hoogendoorn ICLR 2020 [paper](https://arxiv.org/abs/1911.07849)
   
27. **Attentive Group Equivariant Convolutional Networks**  
   David W. Romero, Erik J. Bekkers, Jakub M. Tomczak, Mark Hoogendoorn ICML 2020 [paper](https://arxiv.org/abs/2002.03830)
   
28. **Wavelet Networks: Scale Equivariant Learning From Raw Waveforms**  
   David W. Romero, Erik J. Bekkers, Jakub M. Tomczak, Mark Hoogendoorn [paper](https://arxiv.org/abs/2006.05259)
   
29. **Group Equivariant Stand-Alone Self-Attention For Vision**  
   David W. Romero, Jean-Baptiste Cordonnier ICLR 2021 [paper](https://arxiv.org/abs/2010.00977)
   
30. **MDP Homomorphic Networks: Group Symmetries in Reinforcement Learning**  
   Elise van der Pol, Daniel E. Worrall, Herke van Hoof, Frans A. Oliehoek, Max Welling NeurIPS 2020 [paper](https://arxiv.org/abs/2006.16908)
   
31. **Isometric Transformation Invariant and Equivariant Graph Convolutional Networks**  
   Masanobu Horie, Naoki Morita, Toshiaki Hishinuma, Yu Ihara, Naoto Mitsume ICLR 2021 [paper](https://arxiv.org/abs/2005.06316)
   
32. **E(n) Equivariant Graph Neural Networks**  
   Victor Garcia Satorras, Emiel Hoogeboom, Max Welling ICML 2021 [paper](https://arxiv.org/abs/2102.09844)  
   Note: a simple alternative that achieves E(n) equivariance

33. **Vector Neurons: A General Framework for SO(3)-Equivariant Networks**  
   Congyue Deng, Or Litany, Yueqi Duan, Adrien Poulenard, Andrea Tagliasacchi, Leonidas Guibas  [paper](https://arxiv.org/abs/2104.12229)  
   Note: a simple MLP for type-1 features

34. **Equivariant message passing for the prediction of tensorial properties and molecular spectra**  
Kristof T. Schütt, Oliver T. Unke, Michael Gastegger ICML 2021 [paper](https://arxiv.org/abs/2102.03150)

   

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
  
8. **Universal Equivariant Multilayer Perceptrons**  
Siamak Ravanbakhsh [paper](https://arxiv.org/abs/2002.02912)

9. **Provably Strict Generalisation Benefit for Equivariant Models**  
Bryn Elesedy, Sheheryar Zaidi ICML 2021 [paper](https://arxiv.org/abs/2102.10333)


### [Equivariant Density Estimation and Sampling](#content)

1. **Equivariant Flows: Exact Likelihood Generative Learning for Symmetric Densities**    
  Jonas Köhler, Leon Klein, Frank Noé ICML 2020 [paper](https://arxiv.org/abs/2006.02425)  
  Note: general framework for constructing equivariant normalizing flows on euclidean spaces. Instantiation for particle systems/point clouds = simultanoues SE(3) and permutation equivariance.
2. **Equivariant Hamiltonian Flows**    
  Danilo Jimenez Rezende, Sébastien Racanière, Irina Higgins, Peter Toth NeurIPS 2019 ML4Phys workshop [paper](https://arxiv.org/abs/1909.13739)  
  Note: general framework for constructing equivariant normalizing flows in phase space utilizing Hamiltonian dynamics. Instantiation for SE(2) equivariance.
3. **Sampling using SU(N) gauge equivariant flows**    
  Denis Boyda, Gurtej Kanwar, Sébastien Racanière, Danilo Jimenez Rezende, Michael S. Albergo, Kyle Cranmer, Daniel C. Hackett, Phiala E. Shanahan [paper](https://arxiv.org/abs/2008.05456)    
  Note: normalizing flows for lattice gauge theory. Instantiation for SU(2)/SU(3) equivariance.
4. **Exchangeable neural ode for set modeling**    
  Yang Li, Haidong Yi, Christopher M. Bender, Siyuan Shan, Junier B. Oliva NeurIPS 2020 [paper](https://arxiv.org/abs/2008.02676)  
  Note: framework for permutation equivariant flows for set data. Instantiation for permutation equivariance.
5. **Equivariant Normalizing Flows for Point Processes and Sets**    
  Marin Biloš, Stephan Günnemann NeurIPS 2020 [paper](https://arxiv.org/abs/2010.03242)  
  Note: framework for permutation equivariant flows for set data.  Instantiation for permutation equivariance.
6. **The Convolution Exponential and Generalized Sylvester Flows**    
  Emiel Hoogeboom, Victor Garcia Satorras, Jakub M. Tomczak, Max Welling NeurIPS 2020 [paper](https://arxiv.org/abs/2006.01910)  
  Note: invertible convolution operators. Instantiation for permutation equivariance.
7. **Targeted free energy estimation via learned mappings**    
  Peter Wirnsberger, Andrew J. Ballard, George Papamakarios, Stuart Abercrombie, Sébastien Racanière, Alexander Pritzel, Danilo Jimenez Rezende, Charles Blundell J Chem Phys. 2020 Oct 14;153(14):144112. [paper](https://arxiv.org/abs/2002.04913)  
  Note: normalizing flows for particle systems on a torus. Instantiation for permutation equivariance.
8. **Temperature-steerable flows**    
  Manuel Dibak, Leon Klein, Frank Noé NeurIPS 2020 ML4Phys workshops [paper](https://arxiv.org/abs/2012.00429)  
  Note: normalizing flows in phase space with equivariance with respect to changes in temperature.


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
6. **Ab-Initio Solution of the Many-Electron Schrödinger Equation with Deep Neural Networks**  
  David Pfau, James S. Spencer, Alexander G. de G. Matthews, W. M. C. Foulkes [paper](https://arxiv.org/abs/1909.02487)  
7. **Symmetry-Aware Actor-Critic for 3D Molecular Design**    
  Gregor N. C. Simm, Robert Pinsler, Gábor Csányi, José Miguel Hernández-Lobato ICLR 2021 [paper](https://arxiv.org/abs/2011.12747)
8. **Roto-translation equivariant convolutional networks: Application to histopathology image analysis**  
  Maxime W. Lafarge, Erik J. Bekkers, Josien P.W. Pluim, Remco Duits, Mitko Veta MedIA [paper](https://arxiv.org/abs/2002.08725)
9. **Scale Equivariance Improves Siamese Tracking**  
  Ivan Sosnovik\*, Artem Moskalev\*, Arnold Smeulders WACV 2021 [paper](https://arxiv.org/abs/2007.09115)
10. **3D G-CNNs for Pulmonary Nodule Detection**
  Marysia Winkels, Taco S. Cohen [paper](https://arxiv.org/abs/1804.04656) 
  International Conference on Medical Imaging with Deep Learning (MIDL), 2018.
11. **Roto-translation covariant convolutional networks for medical image analysis**  
  Erik J. Bekkers, Maxime W. Lafarge, Mitko Veta, Koen A.J. Eppenhof, Josien P.W. Pluim, Remco Duits MICCAI 2018 Young Scientist Award [paper](https://arxiv.org/abs/1804.03393)
12. **Equivariant Spherical Deconvolution: Learning Sparse Orientation Distribution Functions from Spherical Data**  
  Axel Elaldi\*, Neel Dey\*, Heejong Kim, Guido Gerig, Information Processing in Medical Imaging (IPMI) 2021 [paper](https://arxiv.org/abs/2102.09462)
13. **Rotation-Equivariant Deep Learning for Diffusion MRI**  
  Philip Müller, Vladimir Golkov, Valentina Tomassini, Daniel Cremers [paper](https://arxiv.org/abs/2102.06942)
14. **Equivariant geometric learning for digital rock physics: estimating formation factor and effective permeability tensors from Morse graph**  
Chen Cai, Nikolaos Vlassis, Lucas Magee, Ran Ma, Zeyu Xiong, Bahador Bahmani, Teng-Fong Wong, Yusu Wang, WaiChing Sun [paper](https://arxiv.org/abs/2104.05608)  
Note: equivariant nets + Morse graph for permeability tensor prediction
15. **Direct prediction of phonon density of states with Euclidean neural network**
Zhantao Chen, Nina Andrejevic, Tess Smidt, Zhiwei Ding, Yen-Ting Chi, Quynh T. Nguyen, Ahmet Alatas, Jing Kong, Mingda Li, Advanced Science (2021) [paper](https://onlinelibrary.wiley.com/doi/10.1002/advs.202004214) [arXiv](https://arxiv.org/abs/2009.05163)
16. **SE(3)-equivariant prediction of molecular wavefunctions and electronic densities**
Oliver T. Unke, Mihail Bogojeski, Michael Gastegger, Mario Geiger, Tess Smidt, Klaus-Robert Müller [paper](https://arxiv.org/abs/2106.02347)


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


### [Talk and Tutorial](#content)

IAS: [Graph Nets: The Next Generation - Max Welling - YouTube](https://www.youtube.com/watch?v=Wx8J-Kw3fTA&t=3602s)

[Equivariance and Data Augmentation workshop](https://sites.google.com/view/equiv-data-aug/home): many nice talks

IPAM: [Tess Smidt: "Euclidean Neural Networks for Emulating Ab Initio Calculations and Generating Atomi..." - YouTube](https://www.youtube.com/watch?v=8CF8Grb_brE)

IPAM: [E(3) Equivariant Neural Network Tutorial ](https://blondegeek.github.io/e3nn_tutorial/)

IPAM: [Risi Kondor: "Fourier space neural networks" ](https://www.youtube.com/watch?v=-PVyi0Keiec)

[NeurIPS 2020 tutorial: Equivariant Networks](https://nips.cc/virtual/2020/public/tutorial_3e267ff3c8b6621e5ad4d0f26142892b.html)

[Yaron Lipman - Deep Learning of Irregular and Geometric Data - YouTube](https://www.youtube.com/watch?v=fveyx5zKReo&feature=youtu.be)

Math-ML: [Erik J Bekkers: Group Equivariant CNNs beyond Roto-Translations: B-Spline CNNs on Lie Groups](https://youtu.be/rakcnrgX4oo)

Kostas Daniilidis: [Geometry-aware deep learning: A brief history of equivariant representations and recent results](https://mathinstitutes.org/videos/videos/view/15146)

Andrew White: [ Deep Learning for Molecules and Materials.](https://whitead.github.io/dmol-book/dl/Equivariant.html)



### [Background](#content)

I am by no means an expert in this field. Here are books and articles suggest by Taco Cohen when asked references to learn group theory and representation theory.

1. [Carter, Visual Group Theory](https://www.amazon.com/Visual-Group-Theory-Problem-Book/dp/088385757X)   
  Note: very basic intro to group theory

2. [Theoretical Aspects of Group Equivariant Neural Networks](https://arxiv.org/abs/2004.05154)  
Carlos Esteves  
Note: covers all the math you need for equivariant nets in a fairly compact and accessible manner.

3. [Serre, Linear Representations of Finite Groups](http://www.math.tau.ac.il/~borovoi/courses/ReprFG/Hatzagot.pdf)   
Note: classic text on representations of finite groups. First few chapters are relevant to equivariant nets.

4. [G B Folland. A Course in Abstract Harmonic Analysis](https://sv.20file.org/up1/1415_0.pdf)   
Note: covers representations of locally compact groups; induced representations.

5. [David Gurarie. Symmetries and Laplacians: Introduction to Harmonic Analysis, Group Representations and Applications.](https://www.amazon.com/Symmetries-Laplacians-Introduction-Representations-Applications/dp/0486462889)  

6. [Mark Hamilton. Mathematical Gauge Theory: With Applications to the Standard Model of Particle Physics](https://www.amazon.com/Mathematical-Gauge-Theory-Applications-Universitext/dp/3319684388)   
Note: covers fiber bundles, useful for understanding homogeneous G-CNNs and Gauge CNNs.




### [TO READ](#content)
There are many paper I haven't read carefully yet. 

1. **Making Convolutional Networks Shift-Invariant Again**   
  Richard Zhang ICML 2019 [paper](https://arxiv.org/abs/1904.11486)
2. **Probabilistic symmetries and invariant neural networks**  
Benjamin Bloem-Reddy, Yee Whye Teh JMLR [paper](https://arxiv.org/abs/1901.06082)
3. **On Representing (Anti)Symmetric Functions**  
Marcus Hutter [paper](https://arxiv.org/abs/2007.15298)
4. **PDE-based Group Equivariant Convolutional Neural Networks**  
  Bart M.N. Smets, Jim Portegies, Erik J. Bekkers, Remco Duits [paper](https://arxiv.org/abs/2001.09046)

