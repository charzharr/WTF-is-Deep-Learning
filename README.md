# WTF-is-Deep-Learning
My notes, experiences, progress, and resources for building Deep Learning expertise and slaying grad school. \
Focal Topics: Machine Learning, Deep Learning, Computer Vision, Biomedical Imaging
<br><br>
**Plan for 2020**: Intensively read 6 papers a week (1 per day Mon to Sat, review on Sun), and submit notes for each of them. The 6 papers will be divided into 2 general categories: (1) Breadth - aimed at solidifying DL foundations (2) Depth - for advancing relevant expertise for current projects and my dissertation in general.
<br><br>
(Inspired by: [Patrick Liu](https://github.com/patrick-llgc/Learning-Deep-Learning))

### Contents
1. [Resources](#i-resources)
    * Meta-Learning - learning how to learn, effective research, process-focused incremental improvement
    * Papers - sources to keep up with literature
    * Courses - great beginner and PhD-level courses
    * Talks - seminars, conference talks, stand-alone lectures
2. [Paper Notes](#ii-paper-notes)
    - Weekly list of papers I read, notes on the, and publication info

### Search (Cmd-F)
**By Year** - 2002 to 2020 \
**By Conference** -
   e.g. CVPR, NIPS, MICCAI, ICLR, ICCV, ICML, ECCV \
**By Topic Category** -
   e.g. [Gml], [Opt], [Net], [Loc], [Uns], [Ano], [Vid]
   * [Gml] General ML (Thinking Frameworks, Theory, Math, 
   * [Opt] Training & Optimization
   * [Net] Networks (FeatEx Backbones, Modules, Aggregation Methods, Components, Analysis)
   * [Loc] Localization (Object Detection, Segmentation)
   * [Uns] Unsupervised Techniques (GAN, VAE, Self-Supervised, Contrastive)
   * [Ano] Annotation Reduction (Active/Transfer Learning, Semi/Weakly-Supervised)
   * [Vid] Video (Multi-Object Tracking, Temporal Features)

# I. Resources

### Meta-Learning 

Learning how to learn.
* Paper on How to Read a Paper [[pdf](/meta/how_to_read_a_paper.pdf)]
* Andrew Ng - Reading Research Papers & Career Advice [[vid](https://www.youtube.com/watch?v=733m6qBH-jI)]
* How to Release Research Code [[git](https://github.com/paperswithcode/releasing-research-code)]

### Papers

Primary
* Google Scholar - Follow Relevant Authors [[site](https://scholar.google.com/citations?hl=en&view_op=search_authors&mauthors=label:computer_vision)]
* ArXiV Preprints - Computer Vision [[site](https://arxiv.org/list/cs.CV/recent)]
* ArXiV Preprints - Organized-ish [[site](http://www.arxiv-sanity.com/)]
* Open Review [[site](https://openreview.net/)]
* Computer Vision Foundation Open Access [[site](http://openaccess.thecvf.com/menu.py)]
* All NIPS Proceedings [[site](https://papers.nips.cc/)]
* Papers With Code [[site](https://paperswithcode.com/)]

Community Discourse & Mentions
* r/MachineLearning Subreddit [[sub](https://www.reddit.com/r/MachineLearning/)]
* Twitter [[followlist](https://www.reddit.com/r/MachineLearning/comments/5jjzny/d_deep_learning_twitter_loop/)]

### Courses & Books

Fundamentals
* 🌟 All-in-one List of *Many* Topics [[repo](https://github.com/kmario23/deep-learning-drizzle)]
* MIT Patrick Winston - Classic Artifical Intelligence 2010 [[playlist](https://www.youtube.com/playlist?list=PLUl4u3cNGP63gFHB6xb-kVBiQHYe_4hSi)]
* ⭐ Stanford CS231n - CNNs for Visual Recognition [[site](http://cs231n.stanford.edu/)]
* Stanford Andrew Ng - Deep Learning Specialization [[coursera](https://www.coursera.org/specializations/deep-learning)]
* Geoffrey Hinton - NNs for Machine Learning [[playlist](https://www.youtube.com/watch?v=OVwEeSsSCHE&list=PLLssT5z_DsK_gyrQ_biidwvPYCRNGI3iv)]
* Columbia Andreas Mueller - Applied Machine Learning 2020 [[playlist](https://www.youtube.com/playlist?list=PL_pVmAaAnxIRnSw6wiCpSvshFyCREZmlM)]
* Carnegie Mellon University - Array of Deep Learning Courses 2020 [[playlists](https://www.youtube.com/channel/UC8hYZGEkI2dDO8scT8C5UQA/playlists)]

Specialized
* deeplearning.ai - AI for Medicine Specialization [[coursera](https://www.coursera.org/specializations/ai-for-medicine)]
* ⭐ Berkeley Pieter Abbeel - Deep Unsupervised Learning [[playlist](https://www.youtube.com/watch?v=V9Roouqfu-M&list=PLwRJQ4m4UJjPiJP3691u-qWwPGVKzSlNP)]

Books
* Dive into Deep Learning (w/PyTorch Implementations) [[site](http://d2l.ai/index.html)]


### Talks


### Tasks
* Computer Vision Conferences [[site](http://conferences.visionbib.com/Iris-Conferences.html)]
* Biomedical Challenges [[site](https://grand-challenge.org/challenges/)]

# II. Paper Notes

Wish-List - 
Breadth: ML Perspectives
* [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) [[TBP]()] <kbd>NIPS 2015</kbd>
* [Statistical Modeling: The Two Cultures](https://www.semanticscholar.org/paper/Statistical-Modeling%3A-The-Two-Cultures-Breiman/e5df6bc6da5653ad98e754b08f63326c2e52b372) [[TBP](papers/2002_stat_modeling_2cultures.md)] <kbd>2001</kbd>
* [A Few Useful Things to Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) [[TBP](papers/2012_useful_things_about_ml.md)] <kbd>2012</kbd>
* [Measuring the tendency of CNNs to Learn Surface Statistical Regularities](https://arxiv.org/abs/1711.11561) <kbd>2017</kbd>
* [Investigating Human Priors for Playing Video Games](https://arxiv.org/abs/1802.10217) <kbd>ICLR 2018</kbd>

Architectures and Model Components
* [Batch Normalization: Accelerating DNN Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167) [[TBP]()]
* [EfficientNet: Rethinking Model Scaling for CNNs](https://arxiv.org/abs/1905.11946) [[TBP]()] <kbd>ICML 2019</kbd>
* [Selective Kernel Networks](https://arxiv.org/abs/1903.06586)

Breadth: Deep Learning Fundamental Concepts
* [Computing Receptive Fields of CNNs](https://distill.pub/2019/computing-receptive-fields/) [[TBP]()] <kbd>Distill 2019</kbd>
* [Why Momentum Really Works](https://distill.pub/2017/momentum/) [[TBP]()] <kbd>Distill 2017</kbd>
* [Visualizing Neural Networks with the Grand Tour](https://distill.pub/2020/grand-tour/) [[TBP]()] <kbd>Distill 2020</kbd>
* [The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks/) [[TBP]()] <kbd>Distill 2018</kbd>

### Wk6 - 2020.07.27
Biomedical Segmentation + Semi-Supervised Techniques

Classics
* [Curriculum Learning](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT9vGcYUxYV9weXLnfmJStsDKsTAzMEhCUlguczrP3ADMdP2d-P8h6E1JRXalfwG_q7RmelqHYA7p6Y/pub)] <kbd>ICML 2009<kbd>
* [NCE: New Estimation Principle for Unnormalized Statistical Models](http://proceedings.mlr.press/v9/gutmann10a/gutmann10a.pdf) [[]()]


### Wk5 - 2020.07.20
Biomedical Segmentation
* [Survey on Not-So-Supervised Biomedical Image Analysis Methods](https://arxiv.org/abs/1804.06353) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTNAVhQ_9AAozTKfK5pNT_tL3dh-n_nup2DH-a_ISijEX4scmxviUf_LK-f6WZPhvR_CZUu_R2ivIKG/pub)] <kbd>MIA 2018</kbd>
* [Attention U-Net: Learning Where to Look for the Pancreas](https://arxiv.org/abs/1804.03999) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQpK-Q8spAIy346TDsLQVIgtF59Plv1aqFA2wHMj17AUDAAXpVlmxrZ6xWkMx4OQBWkLHHJk_6enzG5/pub)] <kbd>MIDL 2018</kbd>
* [A New Ensemble Learning Framework for 3D Biomedical Image Segmentation](https://arxiv.org/abs/1812.03945) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQsvNH53qejLk6p7ZOGH-9rx-JBLpIK0ooyzPPv5xf7iCiXzWUi9vDdcBK6VCvQ7YY3QicKS0yBv3xp/pub)] <kbd>AAAI 2018</kbd>
* [3D UNet: Learning Dense Volumetric Segmentation from Sparse Annotation](https://arxiv.org/abs/1606.06650) [[Notes](https://docs.google.com/document/d/e/2PACX-1vREDFzO_LbTAzI48jUSg0kwwjCMLaCgOTuQEeJTWMNzXsj-zbKwv1wzJBE1HivNFunK2dB1nie7eqcA/pub)] <kbd>MICCAI 2016</kbd>
* [DenseVoxNet: Automatic 3D Cardio MR Segmentation w/Densely-Connected Volumetric CNNs](https://arxiv.org/abs/1708.00573) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTfLFFWjpy9JoRy_00PUHNLtExj48I6enj9-uGAp8oP7DOyeY2ok7NisD8S_WTtU_SEf1Y1WbTngB9p/pub)] <kbd>MICCAI 2017</kbd>
* [VoxResNet: Deep Voxelwise Residual Networks for Brain Segmentation from 3D MR Images](https://arxiv.org/abs/1608.05895) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTfyqbwzbGVz8MhLwxfC80m0HS9uvX2TlceCwhDPwpxEKvaurZ5SaT5b0v84Ujt6FPmJzRhqVJ856b1/pub)] <kbd>JNeuroImage 2018</kbd>
* [2D Semi-Supervised Medical Image Segmentation via Learning Consistency under Transformations](https://arxiv.org/abs/1911.01218) [[Notes](https://docs.google.com/document/d/e/2PACX-1vST9F-ZTQO0mFV-sS6BRbGooAmqjaCVmpSfLTyE00taELDgI8YoSVhmzT3QmxCjc3kWUAVjRErYu1SQ/pub)] <kbd>MICCAI 2019</kbd>

### Wk4 - 2020.07.13
Depth: Recent Self-Supervised & Semi-Supervised Techniques
* [AMDIM: ALearning Representations by Maximizing Mutual Information Across Views](https://arxiv.org/abs/1906.00910) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT7Gsd3Hp9RgNsJft-iRQQxBEoGCMKnHWXY0DtCSqDHR38EurpHECbGwqneFrXG3aCgr6Cssza2z8kB/pub)] <kbd>NIPS 2019</kbd>
* [PIRL: Self-Supervised Learning of Pretext-Invariant Representations](https://arxiv.org/abs/1912.01991) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSsb9J2PUPIJWDJhWHC0pz-x4ddbJnN2IXnnlwkR9s6bABWtTe2u1xqM_z5vU2kM9ECueksVWPzoLvq/pub)] <kbd>CVPR 2020</kbd>
* [Virtual Adversarial Training: A Regularization ](https://arxiv.org/abs/1704.03976) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQGMoYNBPHsMQkpmHOp6A1Gp-hdfEQF7e88QEUxeXXvSmo2EjMCDdMBWX1MWCyWgHAWvH9hXi5ZvzHH/pub)] <kbd>TPAMI 2018</kbd>

### Wk3 - 2020.07.06
Breadth: Segmentation
* [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQONhlttSJmabntPQdSQK82lcOqdLd2cGawQcIU2U4TutljBFwbzIqAbNu87PJsZDJ-Zb-c0CRKjsHA/pub)] <kbd>MICCAI 2015</kbd>
* [Segmentation Survey (cont.): Image Segmentation Using Deep Learning](https://arxiv.org/abs/2001.05566) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTx0Wt6Tf4cqLLDKo47uCw9AugVEwG7x0YcH4IvCcTCVDM7stfp8BM2RZuaYbYkQ-z7on6uNBg7-bdx/pub)] <kbd>2020</kbd>
* [V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation](https://arxiv.org/abs/1606.04797) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRZ_Twb9b7KY9avO4-uRs21JfGiYR5fKa6QzvJQuZOchYC4mbv2lyogI4iX0Im_Lem7rzGe1RJfvJ-e/pub)] <kbd>3DV 2016</kbd>

Depth: Recent Self-Supervised & Semi-Supervised Techniques
* [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://arxiv.org/abs/2001.07685) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSl0pBzwQE5UFluG5V_cT1kDh4QUVgBExxW_gfwz-HempGGTBocllDwQm7T3H8xmSSUtRCRAqEaJRCd/pub)] <kbd>2020</kbd>
* [Mean Teachers: Weight-Averaged Consistency Targets Improve SemiSL Results](https://arxiv.org/abs/1703.01780) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRDDUqIBJsqA365PgPu3JeymLLeWbkIP8x0Xc_YopjqgyJAo6qeNuTV9o6RE6dzBrWdwr739IeXDB1J/pub)] <kbd>NIPS 2017</kbd>
* [CPC: Representation Learning with Contrastive Predictive Coding](https://arxiv.org/abs/1807.03748) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRR9Euw9K7IP2D8Og_QSNj5Imn4tkxo96-0O2uXV0d_SVNlDQsOvnlhDHtc1l1GqqXxG125w03npOvT/pub)] <kbd>2018</kbd>

### Wk2 - 2020.06.29
Breadth: Faster Training and Segmentation
* [Large Scale Distributed Deep Networks](https://papers.nips.cc/paper/4687-large-scale-distributed-deep-networks) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQWAXjGUkP1XXVsCw5QxFRw7nSG96ypaA2Je_VCUGdmvddqraAmyn0fCsUTCO4fKCEFY-KUy6APLJbE/pub)] <kbd>NIPS 2012</kbd>
* [Segmentation Survey: Image Segmentation Using Deep Learning](https://arxiv.org/abs/2001.05566) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTx0Wt6Tf4cqLLDKo47uCw9AugVEwG7x0YcH4IvCcTCVDM7stfp8BM2RZuaYbYkQ-z7on6uNBg7-bdx/pub)] <kbd>2020</kbd>

Depth: Recent Self-Supervised Techniques
* [RotNet'18: Unsupervised Representation Learning by Predicting Image Rotations](https://arxiv.org/abs/1803.07728) [[Notes](https://docs.google.com/document/d/e/2PACX-1vTs6ZgjAhNHocztgGIp9pW-4fJdcov1HvzqrX2b8KkGG1AE8uwBwB3nkCIGHxI_v8qvVRZhoz_dsZeA/pub)] <kbd>ICLR 2018</kbd>
* [SimClr: A Simple Framework for Contrastive Learning of Visual Representations](https://arxiv.org/abs/2002.05709) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQfMcTFad1_TorKNQYhE2M7CE9XgLAQwuPLvJdXcXmPxZ7EaRbhcXisT_nG0alpke8nd6O3Xua-or6E/pub)] <kbd>2020</kbd>
* [SimClr2: Big Self-Supervised Models are Strong Semi-Supervised Learners](https://arxiv.org/abs/2006.10029) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQjvgDpS65W6SbvSXyB5I0D7Z4p97bfjdAHLEa_cs6-505wctWSYEtOKr72FS8XrWWwozfx3sD-jTFc/pub)] <kbd>2020</kbd>
* [MoCo: Momentum Contrast for Unsupervised Visual Representation Learning](https://arxiv.org/abs/1911.05722) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQs6jb-aWYj3M5AD3TmFgOQmtZUzUP9cJVBWFxxEUjiQFS3Sf62kpK4o3sk-KHiqSdaXSN4j5MGq61i/pub)] <kbd>CVPR 2020</kbd>

### Wk1 - 2020.06.22
Breadth: Classics on Network Components
* [PReLu: Delving Deep into Rectifiers: Surpassing Humans on ImageNet](https://arxiv.org/abs/1502.01852) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRqOwLjzuJ8ZKJUv7EhMS7yh4aGf2-mebJrzYst33eOrpRGt-ap__btUpOwhv0iZvelbIPSgAFIFhZ_/pub)] <kbd>ICCV 2015</kbd>
* [Network in Network](https://arxiv.org/abs/1312.4400) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ4TFpOLHDiMtjfQdmf-XB5_hMkOHlJRe-s45veXK89fsVecz8ub2e5m7UAhcyQod5JbTIzdXFyw4Mj/pub)] <kbd>ICLR 2014</kbd>
* [ResNeXt: Aggregated Residual Transformations for DNNs](https://arxiv.org/abs/1611.05431) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRb2gGDAC2GEicocasLbDZ8MohQRXuqR49Xqyz8P9hWGWw06LApyQ6TX2vaMQw1fyRgN3K7fheHMz1Y/pub)] <kbd>CVPR 2017</kbd>

Depth: Effective Training
* [Bag of Tricks for Image Classification](https://arxiv.org/abs/1812.01187) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSoh0y7XiaE7EWYvT1a_aUUFpIJ0FIrm1h0zGKQBq5RyQno7b3Wg-crOsMgppYCIXi4fM-b2k6v-JHe/pub)] <kbd>CVPR 2019</kbd> 
* [Don't Decay the Learning Rate, Increase the Batch Size](https://arxiv.org/abs/1711.00489) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRhMhpCevNtp3-D8J28Uo47DWj2_i_pP-imYT5vfPqpy0N0Bj2opEduvm3lQiB_ZhplwafqseTQqZUq/pub)] <kbd>ICLR 2018</kbd> 
* [Four Things Everyone Should Know to Improve Batch Normalization](https://arxiv.org/abs/1906.03548) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ_IX5oi94F7dCDkcsYexACrD2Wxbl08vbHqCr0KIsA6tyNuyNcl-169bo-pa3RtTZ1HRAUQ68Mmdon/pub)] <kbd>ICLR 2020</kbd>

### Wk0 - 2020.06.15
(Trial Run) Test and improve the process.
* [How to Read a Paper](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRF38E2y_akvL4NKcfXzoeiPSYz3_73xSIuOk_YGCvjSmMWUcSLzZMa91jgdZc-B-AqkfpT6G6D_BbO/pub)] <kbd>2016</kbd>
* [DLA: Deep Layer Aggregation](https://arxiv.org/abs/1707.06484) [[Notes]()] <kbd>CVPR 2018</kbd>
* [DenseNet: Densely Connected Convolutional Networks](https://arxiv.org/abs/1608.06993) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT41lqeRvSWQdN7Qjc55WheEVzWYINBjNuugH3VVgwXA-HRUW8zhQYBJTdVt51LU5WjI4qHT4iQpihQ/pub)] <kbd>CVPR 2017</kbd>

