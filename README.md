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

Wish-List:
Breadth: ML Perspectives
* [Hidden Technical Debt in Machine Learning Systems](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) [[Notes]()] <kbd>NIPS 2015</kbd>
* [Statistical Modeling: The Two Cultures](https://www.semanticscholar.org/paper/Statistical-Modeling%3A-The-Two-Cultures-Breiman/e5df6bc6da5653ad98e754b08f63326c2e52b372) [[Notes](papers/2002_stat_modeling_2cultures.md)] <kbd>2001</kbd>
* [A Few Useful Things to Know About Machine Learning](https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) [[Notes](papers/2012_useful_things_about_ml.md)] <kbd>2012</kbd>

### Wk2 - 2020.06.29
Breadth: Classic Architectures
Depth: Newer Architectures
* [EfficientNet: Rethinking Model Scaling for CNNs](https://arxiv.org/abs/1905.11946) [[Notes]()] <kbd>ICML 2019</kbd>

### Wk1 - 2020.06.22
Breadth: Classics on Network Components
* [Delving Deep into Rectifiers: Surpassing Humans on ImageNet](https://arxiv.org/abs/1502.01852) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRqOwLjzuJ8ZKJUv7EhMS7yh4aGf2-mebJrzYst33eOrpRGt-ap__btUpOwhv0iZvelbIPSgAFIFhZ_/pub)] <kbd>ICCV 2015</kbd>
* [Network in Network](https://arxiv.org/abs/1312.4400) [[Notes](https://docs.google.com/document/d/e/2PACX-1vQ4TFpOLHDiMtjfQdmf-XB5_hMkOHlJRe-s45veXK89fsVecz8ub2e5m7UAhcyQod5JbTIzdXFyw4Mj/pub)] <kbd>2013</kbd>
* [Aggregated Residual Transformations for DNNs](https://arxiv.org/abs/1611.05431) [[Notes]()] <kbd>CVPR 2017</kbd>

Depth: Effective Training
* [Bag of Tricks for Image Classification](https://arxiv.org/abs/1812.01187) [[Notes](https://docs.google.com/document/d/e/2PACX-1vSoh0y7XiaE7EWYvT1a_aUUFpIJ0FIrm1h0zGKQBq5RyQno7b3Wg-crOsMgppYCIXi4fM-b2k6v-JHe/pub)] <kbd>CVPR 2019</kbd> 
* [Don't Decay the Learning Rate, Increase the Batch Size](https://arxiv.org/abs/1711.00489) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRhMhpCevNtp3-D8J28Uo47DWj2_i_pP-imYT5vfPqpy0N0Bj2opEduvm3lQiB_ZhplwafqseTQqZUq/pub)] <kbd>2017</kbd> 


### Wk0 - 2020.06.15
(Trial Run) Test and improve the process.
* [How to Read a Paper](http://blizzard.cs.uwaterloo.ca/keshav/home/Papers/data/07/paper-reading.pdf) [[Notes](https://docs.google.com/document/d/e/2PACX-1vRF38E2y_akvL4NKcfXzoeiPSYz3_73xSIuOk_YGCvjSmMWUcSLzZMa91jgdZc-B-AqkfpT6G6D_BbO/pub)] <kbd>2016</kbd>
* [DLA: Deep Layer Aggregation](https://arxiv.org/abs/1707.06484) [[Notes]()] <kbd>CVPR 2018</kbd>
* [DenseNet: Densely Connected Convolutional Networks](https://arxiv.org/abs/1608.06993) [[Notes](https://docs.google.com/document/d/e/2PACX-1vT41lqeRvSWQdN7Qjc55WheEVzWYINBjNuugH3VVgwXA-HRUW8zhQYBJTdVt51LU5WjI4qHT4iQpihQ/pub)] <kbd>CVPR 2017</kbd>

