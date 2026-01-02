---
layout: page
---

# Eli N. Weinstein

<img src="/images/Eli_Weinstein_v2.png" alt="drawing" width="150" align="left" hspace="10">

I am an assistant professor of chemistry at the Technical University of Denmark (DTU). I'm also a member of ELLIS and the Pioneer Centre for AI.

I work on fundamental methodology in machine learning for molecules. 
I focus especially on developing probabilistic methods to steer laboratory experiments (experimental design) 
and to learn from natural experiments and observation (causal inference). I am motivated by
foundational questions of how to learn about the molecular world, including how to efficiently learn molecule-activity relationships, and how to estimate molecules' effects on complex biological systems.

If you would like to read more, I recommend my papers on [steering stochastic chemical reactions](https://proceedings.mlr.press/v151/weinstein22a) 
to [synthesize DNA from generative models at scale](https://www.biorxiv.org/content/10.1101/2024.09.13.612900v3), or on 
[hierarchical causal modeling](https://arxiv.org/abs/2401.05330) and its application to [human immune receptor repertoires](https://arxiv.org/abs/2410.14127).

My fundamental research is often motivated by applied problems in therapeutics and drug discovery. 
I am part-time Director of Machine Learning Research at [Jura Bio](https://www.jura.bio), a genomic medicines startup, where my methods have been translated into
therapeutic discovery and development.

Previously, I was a postdoctoral research scientist with [David Blei](http://www.cs.columbia.edu/~blei/) in the Data Science Institute at Columbia University.
I received my PhD in Biophysics from Harvard University in 2022, advised by [Debora Marks](https://marks.hms.harvard.edu/index.html) and [Jeff Miller](https://jwmi.github.io/), as a [Hertz Foundation Fellow](https://www.hertzfoundation.org/). 
I received my A.B. in Chemistry and Physics with highest honors from Harvard in 2016, working with [Adam Cohen](http://cohenweb.rc.fas.harvard.edu/).

Please reach out if you are interested in working with me or collaborating.

Email: enawe [at] dtu.dk

**If you are interested in attending the ML & Molecules Reading Group at DTU, please click [here]({{ site.baseurl }}/mlmol).**

## Publications and preprints
\*Equal contribution (first or last author)


### Experimental Design

**Eli N. Weinstein\***, Andrei Slabodkin\*, Mattia G. Gollub\*, Kerry Dobbs\*, Xiao-Bing Cui\*, Fang Zhang, Kristina Gurung, Elizabeth B. Wood.
*Lifting biomolecular data acquisition.* 2025. Preprint. [paper](https://arxiv.org/abs/2512.15984v1). [blog](https://www.jura.bio/blog/leavs).\
<sub> We develop a method to pack and extract more information from high throughput experiments, using variational synthesis (below). It is based on an extension of compressed sensing, from learning vectors to learning functions parameterized by neural networks. <sub>


**Eli N. Weinstein\***, Andrei Slabodkin\*, Mattia G. Gollub\*, Elizabeth B. Wood. *Accelerated learning on large scale screens using generative library models.* 2025. In submission. [paper](https://arxiv.org/abs/2510.16612). [blog](https://www.jura.bio/blog/leavs).\
<sub> We develop a method to scale up learning of protein function. It is based on the co-design of experiments and inference algorithms, taking advantage of variational synthesis (below).<sub>

**Eli N. Weinstein\***, Mattia G. Gollub\*, Andrei Slabodkin\*, Cameron L. Gardner, Kerry Dobbs, Xiao-Bing Cui, Alan N. Amin, George M. Church, Elizabeth B. Wood. *Manufacturing-aware generative model architectures enable biological sequence design and synthesis at petascale.* 2024. Accepted at Nature Biotechnology. [paper](https://www.biorxiv.org/content/10.1101/2024.09.13.612900v3). [blog](https://www.jura.bio/blog/variationalsynthesis).\
<sub>We develop a method that reduces the cost of synthesizing proteins designed by a 
generative model by as much as a trillion-fold. This work implements variational synthesis (below) in the laboratory. 
At Jura Bio, we are using it for therapeutic discovery. A short version of this paper won a best paper award (top 4) at 
the Molecular Machine Learning Conference (MoML) 2024.</sub>

**Eli N. Weinstein**, Alan N. Amin, Will Grathwohl, Adeline Kassler, Jean Disset, Debora S. Marks. *Optimal design of stochastic DNA synthesis protocols based on generative sequence models.* Artificial Intelligence and Statistics (AISTATS). 2022. [paper](https://proceedings.mlr.press/v151/weinstein22a). [code](https://github.com/debbiemarkslab/variational-synthesis). [talk](https://www.youtube.com/watch?v=_h0S9pmcwgI&ab_channel=MLforproteinengineeringseminarseries).\
<sub>We develop an experimental design method to efficiently manufacture samples from generative models in the real world.</sub>

### Causal Inference

**Eli N. Weinstein**, David M. Blei. *Hierarchical causal models.* 2024. Revise & resubmit at JMLR. [paper](https://arxiv.org/abs/2401.05330). [code](https://github.com/EWeinstein/HCM). [talk](https://www.youtube.com/watch?v=ovOVaNMxN8c&ab_channel=ClimbSeminars).\
<sub>We develop methods to draw causal inferences from nested data.</sub>

**Eli N. Weinstein**, Elizabeth B. Wood, David M. Blei. *Estimating the causal effects of T cell receptors*. 2024. In submission. 
[paper](https://arxiv.org/abs/2410.14127).\
<sub>We estimate the effect of T cells with a specific TCR on patient outcomes. This work uses hierarchical causal models (above).<sub>

### Nonparametric Methods

Alan N. Amin, Debora S. Marks\*, **Eli N. Weinstein\***. *Biological sequence kernels with guaranteed flexibility.* 2025. Journal of Machine Learning Research. [paper](https://jmlr.org/papers/v26/23-0455.html). \
<sub>We analyze the flexibility of kernels for biological sequences. 
We find problems with many popular kernels, and propose fixes, enabling consistent nonparametric regression and two-sample tests.
Alan won a best student paper award at the New England Statistics Symposium 2023 for this work.</sub>

Alan N. Amin, **Eli N. Weinstein\***, Debora S. Marks\*. *A kernelized Stein discrepancy for biological sequences.* International Conference on Machine Learning (ICML). 2023. [paper](https://openreview.net/forum?id=8LdBTjylEw).\
<sub>We develop a new discrepancy for biological sequence distributions. It can be used (for instance) to measure the goodness-of-fit of a generative sequence model, or the quality of samples drawn from a generative sequence model.</sub>

Alan N. Amin\*, **Eli N. Weinstein\***, Debora S. Marks. *A generative nonparametric Bayesian model for whole genomes*. Advances in Neural Information Processing Systems (NeurIPS). 2021. [paper](https://proceedings.neurips.cc/paper/2021/hash/e9dcb63ca828d0e00cd05b445099ed2e-Abstract.html). [code](https://github.com/debbiemarkslab/BEAR). [talk](https://www.youtube.com/watch?v=bR8Ct75w3YE&t=2737s). \
<sub>We develop a scalable nonparametric model for biological sequences, and establish its asymptotic consistency and convergence rate.
We also apply this model to develop goodness-of-fit and two-sample tests for biological sequences.</sub>

### Model Misspecification

Bohan Wu\*, **Eli N. Weinstein\***, Sohrab Salehi, Yixin Wang, David M. Blei. *Adaptive nonparametric perturbations of parametric Bayesian models.* 2024. Revise & resubmit at JMLR. [paper](https://arxiv.org/abs/2412.10683). [code](https://github.com/bohanwu424/npp).\
<sub>We develop a technique to robustify Bayesian models, guarding against model misspecification while preserving data efficiency.<sub>

**Eli N. Weinstein**, Jeffrey W. Miller. *Bayesian data selection.* Journal of Machine Learning Research. 2023. [paper](https://www.jmlr.org/papers/v24/21-1067.html). [code](https://github.com/EWeinstein/data-selection). [talk](https://neurips.cc/virtual/2021/workshop/21872#wse-detail-36907).\
<sub>We develop a technique to discover the aspects of a data set that a Bayesian model can explain, and those it cannot.
This work received a best student paper award at the New England Statistics Symposium, 2021. 
A workshop version was selected for a contributed talk at the Your Model is Wrong workshop, NeurIPS 2021.</sub>

**Eli N. Weinstein\***, Alan N. Amin\*, Jonathan Frazer, Debora S. Marks. *Non-identifiability and the blessings of misspecification in models of molecular fitness and phylogeny.* Advances in Neural Information Processing Systems (NeurIPS). 2022. [paper](https://openreview.net/pdf?id=CwG-o0ind6t). [talk](https://harvard.zoom.us/rec/share/NFsmlTHeL9FQb1V1MnJtKaG9sImezdX3cwlFadP22euNED__1WInzXteUUYMxPeB.YLiCg84HOz0yzYAO).\
<sub>We analyze the fundamental limits of what generative sequence models can learn about protein evolution, and propose biophysical and statistical reasons for their empirical success as fitness estimators.
This paper won an oral presentation at NeurIPS.</sub>

### Additional work

Bohan Wu, Eli N. Weinstein, David M. Blei. *Bayesian Empirical Bayes: Simultaneous Inference from Probabilistic Symmetries.* In submission. 2025.
[paper](https://arxiv.org/pdf/2512.16239)\
<sub>We develop methods to reconstruct latent variables from complex structured data. The methods leverage group theory to learn from a single graph, array, spatiotemporal process, molecule, etc.<sub>

Erik Nijkamp, Jeffrey Ruffolo, **Eli N. Weinstein**, Nikhil Naik, Ali Madani. *ProGen2: exploring the boundaries of protein language models.* Cell Systems. 2023. 
[paper](https://www.cell.com/cell-systems/abstract/S2405-4712(23)00272-7)\
<sub>The team explored very large scale generative sequence models, trained on a massive sequence datasets. 
The results they found were in line with the theory developed in our previous [paper](https://openreview.net/pdf?id=CwG-o0ind6t).
I contributed by helping to interpret and explain these results.</sub>

David Ding, Anna G Green, Boyuan Wang, Thuy-Lan Vo Lite, **Eli N. Weinstein**, Debora S Marks, Michael T Laub. 
*Co-evolution of interacting proteins through non-contacting and non-specific mutations.* Nature Ecology and Evolution. 2022. [paper](https://www.nature.com/articles/s41559-022-01688-0)\
<sub>The team performed one of the first deep mutational scans of a protein-protein interaction. I helped build the Bayesian model used to analyze the data.</sub>

**Eli N. Weinstein**, Debora S. Marks. *A structured observation distribution for generative biological sequence prediction and forecasting.* International Conference on Machine Learning (ICML). 2021. [paper](http://proceedings.mlr.press/v139/weinstein21a.html). [Pyro code](https://docs.pyro.ai/en/dev/contrib.mue.html). [Edward2 code](https://github.com/debbiemarkslab/MuE). [talk](https://www.youtube.com/watch?v=bR8Ct75w3YE&t=2737s).\
<sub>We develop an observation distribution for biological sequences, which enables (for instance) regression from covariates to sequences.
We apply this model to develop a generative forecast of viral antigen evolution.</sub>

Evangelos Kiskinis\*, Joel M Kralj\*, Peng Zou\*, **Eli N. Weinstein\***, Hongkang Zhang, Konstantinos Tsioras, Ole Wiskow, J Alberto Ortega, Kevin Eggan, Adam E Cohen.
*All-optical electrophysiology for high-throughput functional characterization of a human iPSC-derived motor neuron model of ALS.* Stem Cell Reports. 2018. [paper](https://www.sciencedirect.com/science/article/pii/S2213671118301887)\
<sub>The team developed a high-throughput screening platform for measuring the electrophysiological properties of human neurons. I built a computational pipeline for analyzing the data.
I also helped translate these tools, together with additional machine learning techniques, into the therapeutic discovery platform at Q-State Biosciences (now [Quiver Biosciences](https://www.quiverbioscience.com/)).</sub>

Shan Lou, Yoav Adam, **Eli N. Weinstein**, Erika Williams, Katherine Williams, Vicente Parot, Nikita Kavokine, Stephen Liberles, Linda Madisen, Hongkui Zeng, Adam E Cohen.
*Genetically targeted all-optical electrophysiology with a transgenic Cre-dependent optopatch mouse.* Journal of Neuroscience. 2016. [paper](https://www.jneurosci.org/content/36/43/11059?utm_source=TrendMD&utm_medium=cpc&utm_campaign=JNeurosci_TrendMD_0)\
<sub>The team developed a transgenic mouse for optical electrophysiology studies in genetically-defined subsets of cells. I built a computational pipeline for analyzing the data.</sub>

### PhD Thesis

Eli N. Weinstein. Generative Statistical Methods for Biological Sequences. Harvard University. 2022. [pdf](papers/dissertation.pdf)

#### [Google scholar](https://scholar.google.com/citations?user=Tkv7cWAAAAAJ&hl=en).
