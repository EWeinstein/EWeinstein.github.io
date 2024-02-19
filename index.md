---
layout: page
---

# Eli N. Weinstein

<img src="/images/Eli_Weinstein_square.jpeg" alt="drawing" width="150" align="left" hspace="10">


I'm a postdoctoral research scientist working with [David Blei](http://www.cs.columbia.edu/~blei/) at Columbia University. 
I also lead machine learning research at [Jura Bio](https://www.jura.bio), a genomic medicines startup. 
Broadly, I work in the fields of probabilistic machine learning and Bayesian statistics, and their application to biophysics and genomics.

I received my PhD in Biophysics from Harvard University in 2022, advised by [Debora Marks](https://marks.hms.harvard.edu/index.html) and working closely with [Jeff Miller](https://jwmi.github.io/), as a [Hertz Foundation Fellow](https://www.hertzfoundation.org/). 
I received my A.B. in Chemistry and Physics with highest honors from Harvard in 2016, working with [Adam Cohen](http://cohenweb.rc.fas.harvard.edu/).

My research spans from theoretical machine learning to applied computational biology. 
I am especially motivated by foundational methodological questions in computational biology,
particularly in synthetic biology. If you would like to learn about some of my recent work, I recommend my papers on 
[hierarchical causal models](https://arxiv.org/abs/2401.05330) or [variational DNA synthesis](https://proceedings.mlr.press/v151/weinstein22a).


Email: ew2760 [at] columbia.edu

## Publications and preprints
\*Equal contribution (first or last author)

### General machine learning methodology

**Eli N. Weinstein**, David M. Blei. *Hierarchical causal models.* 2024. In submission. [paper](https://arxiv.org/abs/2401.05330). [code](https://github.com/EWeinstein/HCM). [talk](https://www.youtube.com/watch?v=ovOVaNMxN8c&ab_channel=ClimbSeminars).\
<sub>We develop methods to draw causal inferences from nested data.</sub>

**Eli N. Weinstein**, Jeffrey W. Miller. *Bayesian data selection.* Journal of Machine Learning Research. 2023. (IBM Student Paper Award at the New England Statistics Symposium 2021, Contributed talk at the Your Model is Wrong workshop, NeurIPS 2021.) [paper](https://www.jmlr.org/papers/v24/21-1067.html). [code](https://github.com/EWeinstein/data-selection). [talk](https://neurips.cc/virtual/2021/workshop/21872#wse-detail-36907).\
<sub>We develop a technique to discover the aspects of a data set that a Bayesian model can explain, and those it cannot.</sub>

### Methodology for biological sequences

Alan N. Amin, **Eli N. Weinstein\***, Debora S. Marks\*. *Biological Sequence Kernels with Guaranteed Flexibility.* 2023. In submission.  (Alan won the MassMutual Student Research Award at the New England Statistics Symposium 2023 for this work). [paper](https://arxiv.org/abs/2304.03775). \
<sub>We analyze the flexibility of kernels for biological sequences. 
We find problems with many popular kernels, and propose fixes.</sub>

Alan N. Amin, **Eli N. Weinstein\***, Debora S. Marks\*. *A Kernelized Stein Discrepancy for Biological Sequences.* International Conference on Machine Learning (ICML). 2023. [paper](https://openreview.net/forum?id=8LdBTjylEw).\
<sub>We develop a new discrepancy for biological sequence distributions. It can be used (for instance) to measure the goodness-of-fit of a generative sequence model, or the quality of samples drawn from a generative sequence model.</sub>

**Eli N. Weinstein\***, Alan N. Amin\*, Jonathan Frazer, Debora S. Marks. *Non-identifiability and the blessings of misspecification in models of molecular fitness and phylogeny.* Advances in Neural Information Processing Systems (NeurIPS). 2022. **Oral presentation.** [paper](https://openreview.net/pdf?id=CwG-o0ind6t). [talk](https://harvard.zoom.us/rec/share/NFsmlTHeL9FQb1V1MnJtKaG9sImezdX3cwlFadP22euNED__1WInzXteUUYMxPeB.YLiCg84HOz0yzYAO).\
<sub>We analyze the fundamental limits of what generative sequence models can learn about protein evolution, and propose biophysical and statistical reasons for their empirical success as fitness estimators.</sub>

**Eli N. Weinstein**, Alan N. Amin, Will Grathwohl, Daniel Kassler, Jean Disset, Debora S. Marks. *Optimal design of stochastic DNA synthesis protocols based on generative sequence models.* Artificial Intelligence and Statistics (AISTATS). 2022. [paper](https://proceedings.mlr.press/v151/weinstein22a). [code](https://github.com/debbiemarkslab/variational-synthesis). [talk](https://www.youtube.com/watch?v=_h0S9pmcwgI&ab_channel=MLforproteinengineeringseminarseries).\
<sub>We develop an experimental design strategy for efficiently synthesizing samples from generative sequence models in the laboratory (variational synthesis).
At Jura Bio, we are using this method to build high quality, large scale libraries for therapeutic discovery.</sub>

Alan N. Amin\*, **Eli N. Weinstein\***, Debora S. Marks. *A generative nonparametric Bayesian model for whole genomes*. Advances in Neural Information Processing Systems (NeurIPS). 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/e9dcb63ca828d0e00cd05b445099ed2e-Abstract.html). [code](https://github.com/debbiemarkslab/BEAR). [talk](https://www.youtube.com/watch?v=bR8Ct75w3YE&t=2737s). \
<sub>We develop a scalable nonparametric model for biological sequences, and establish its asymptotic consistency and convergence rate.
We also apply this model to develop goodness-of-fit and two-sample tests for biological sequences.</sub>

**Eli N. Weinstein**, Debora S. Marks. *A structured observation distribution for generative biological sequence prediction and forecasting.* International Conference on Machine Learning (ICML). 2021. [paper](http://proceedings.mlr.press/v139/weinstein21a.html). [Pyro code](https://docs.pyro.ai/en/dev/contrib.mue.html). [Edward2 code](https://github.com/debbiemarkslab/MuE). [talk](https://www.youtube.com/watch?v=bR8Ct75w3YE&t=2737s).\
<sub>We develop an observation distribution for biological sequences, which enables (for instance) regression from covariates to sequences.
We apply this model to develop a generative forecast of viral antigen evolution.</sub>

### Collaborations / applications

Erik Nijkamp, Jeffrey Ruffolo, **Eli N Weinstein**, Nikhil Naik, Ali Madani. *ProGen2: Exploring the Boundaries of Protein Language Models.* 2022. 
[paper](https://arxiv.org/pdf/2206.13517.pdf)\
<sub>The team explored very large scale generative sequence models, trained on a massive sequence datasets. 
The results they found were in line with the theory developed in our previous [paper](https://openreview.net/pdf?id=CwG-o0ind6t).
I contributed by helping to interpret and explain these results.</sub>

David Ding, Anna G Green, Boyuan Wang, Thuy-Lan Vo Lite, **Eli N Weinstein**, Debora S Marks, Michael T Laub. 
*Co-evolution of interacting proteins through non-contacting and non-specific mutations.* Nature Ecology and Evolution. 2022. [paper](https://www.nature.com/articles/s41559-022-01688-0)\
<sub>The team performed one of the first deep mutational scans of a protein-protein interaction. I helped build the Bayesian model used to analyze the data.</sub>

Evangelos Kiskinis\*, Joel M Kralj\*, Peng Zou\*, **Eli N Weinstein\***, Hongkang Zhang, Konstantinos Tsioras, Ole Wiskow, J Alberto Ortega, Kevin Eggan, Adam E Cohen.
*All-optical electrophysiology for high-throughput functional characterization of a human iPSC-derived motor neuron model of ALS.* Stem Cell Reports. 2018. [paper](https://www.sciencedirect.com/science/article/pii/S2213671118301887)\
<sub>The team developed a high-throughput screening platform for measuring the electrophysiological properties of human neurons. I built a computational pipeline for analyzing the data.
I also helped translate these tools, together with additional machine learning techniques, into the therapeutic discovery platform at Q-State Biosciences (now [Quiver Biosciences](https://www.quiverbioscience.com/)).</sub>

Shan Lou, Yoav Adam, **Eli N Weinstein**, Erika Williams, Katherine Williams, Vicente Parot, Nikita Kavokine, Stephen Liberles, Linda Madisen, Hongkui Zeng, Adam E Cohen.
*Genetically targeted all-optical electrophysiology with a transgenic Cre-dependent optopatch mouse.* Journal of Neuroscience. 2016. [paper](https://www.jneurosci.org/content/36/43/11059?utm_source=TrendMD&utm_medium=cpc&utm_campaign=JNeurosci_TrendMD_0)\
<sub>The team developed a transgenic mouse for optical electrophysiology studies in genetically-defined subsets of cells. I built a computational pipeline for analyzing the data.</sub>

### PhD Thesis

Eli N. Weinstein. Generative Statistical Methods for Biological Sequences. Harvard University. 2022. [pdf](papers/dissertation.pdf)

#### [Google scholar](https://scholar.google.com/citations?user=Tkv7cWAAAAAJ&hl=en).
