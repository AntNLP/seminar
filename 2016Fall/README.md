# AntNLP seminar slides -- 2016 Fall

Time: 9:00 am, Friday

Venue: Science Building B914

**Upcoming: 2017 Spring**
- Dependency Parsing
- Question Answering


## Ref
- http://nlp.stanford.edu/read/
- https://nndl.github.io/seminar2016fall
- https://arxiv.org/list/cs.CL/recent
- http://aclweb.org/anthology/

## DependencyParsing

### [DependencyParsing](https://github.com/AntNLP/seminar/tree/master/2016Fall/DependencyParsing)
- [Tutorial from Mcdonald and Nirve](http://www.ryanmcd.com/courses/esslli2007/)
  - IntroToDataDrivenDependencyParsing1(Outline)
  - IntroToDataDrivenDependencyParsing2(Machine Learning)
  - IntroToDataDrivenDependencyParsing3(Transition-based Models)
  - IntroToDataDrivenDependencyParsing4(Graph-based Models)
  - IntroToDataDrivenDependencyParsing5(Loose End)
- Graph based dependency parsing
  - [COLING96] Three new probabilistic models for dependency parsing: An exploration
  - [EMNLP05] Non-projective Dependency Parsing using Spanning Tree Algorithms
- Transition based dependency parsing
  - [CL08] Algorithms for Deterministic IncrementalDependency Parsing
  - [ACL10] Dynamic Programming for Linear-Time Incremental Parsing
  - [TACL13] Training Deterministic Parsers with Non-Deterministic Oracles
- Dependency parsing in NN
  - Deep Biaffine Attention For Neural Dependency Parsing
  - Structured Training for Neural Network Transition-Based Parsing
- Slides
  - Three New Probabilistic Models.pptx
  - DEEP BIAFFINE ATTENTION.pptx
  - Structured Training for Neural Network Transition-Based Parsing acl15slides.pptx


## Memory Networks

### [Memory Networks (I)](https://github.com/AntNLP/seminar/tree/master/2016Fall/Memory%20Networks%20(I))
- ICLR15-Facebook-MEMORY NETWORKS.pdf
- NIPS15-NYU-End-To-End Memory Networks.pdf
- Variant
  - ICML16-Socher-Ask Me Anything Dynamic Memory Networks for Natural Language Processing.pdf
- Application
  - EMNLP16-FDU-5-EMNLP16-FDU-Deep Multi-Task Learning with Shared Memory.pdf
  - NAACL16-Ke Tran-Recurrent Memory Networks for Language Modeling.pdf
  - EMNLP16-HIT-Aspect Level Sentiment Classification with Deep Memory Network.pdf
- Slides
  - Memory Network.pptx
  - MemNN.ppt

### [Memory Networks (II) -- Neural Turing Machines](https://github.com/AntNLP/seminar/tree/master/2016Fall/Memory%20Networks%20(II)%20--%20Neural%20Turing%20Machines)
- Code
  - [tensorflow MemN2N](https://github.com/domluna/memn2n)
  - MemN2N--CodeAnalysis.pptx
- Memory Networks
  - 1. arXiv16-Bengio-Hierachical Memory Networks
- Neural Turing Machines
  - 2. arXiv14-DeepMind-Neural Turing Machines
  - 3. nature20101-DeepMind-Hybrid computing using a neural network with dynamic external memory
-Slides
  - NTM.ppt

## Word Embedding
### [Word Embeddings (I) -- Basic Concepts](https://github.com/AntNLP/seminar/tree/master/2016Fall/Word%20Embeddings%20(I))
- NNLM
  - Bengio et al. - 2003 - A neural probabilistic language model
- C&W
  - Collobert et al. - 2011 - Natural language processing (almost) from scratch
- Huang et al. - 2012 - Improving Word Representations via Global Context and Multiple Word Prototypes
- Mnih and Kavukcuoglu - 2013 - Learning word embeddings efficiently with noise-contrastive estimation
- CBOW & Skip-gram
  - Mikolov et al. - 2013 - Distributed representations of words and phrases and their Compositionality
  - Mikolov et al. - 2013 - Efficient estimation of word representations in Vector Space
  - code: https://code.google.com/archive/p/word2vec/
- GloVe
  - Pennington et al. - 2014 - Glove Global Vectors for Word Representation
  - code: https://github.com/stanfordnlp/GloVe
- Sides
  - slides-word_embedding.pdf
  - slides-MultiplePrototypes.pdf

### [Word Embeddings (II) -- Co-occur Matrix and Sparsity](https://github.com/AntNLP/seminar/tree/master/2016Fall/Word%20Embeddings%20(II))
- word2vec as matrix factorization
  - **NIPS14-Levy and Goldberg-Neural word embedding as implicit matrix factorization**
- Optimizing Word Representation
  - Sparse Representation
    - ACL15-CMU-Sparse Overcomplete Word Vector Representations
    - ACL16-PKU-Compressing Neural Language Models by Sparse Word Representations
  - Incorporating Semantics
    - ACL16-Yandex-Siamese CBOW Optimizing Word Embeddings for Sentence Representations
    - NIPS15-Ryan-Skip-Thought Vectors
    - NAACL16-USTC-Improve ChineseWord Embeddings by Exploiting Internal Structure
- Hierarchical Attentive Memory
  - **arXiv16-Learning Efficient Algorithms with Hierarchical Attentive Memory**
- Batch Normalization
  - **ICML15-Ioffe and Szegedy-Batch Normalization Accelerating Deep Network Training by Reducing Internal Covariate Shift**
- Slides
  - Slides-Optimizing Word Embedding & Hierachical Attentive Memory.ppt
  - Slides-MF & BN.pdf

## GANs
### [GANS (I)](https://github.com/AntNLP/seminar/tree/master/2016Fall/GANs%20(I))
- Goodfellow-2014-Generative-adversarial-nets.pdf
- Slides
  - Slides-Gans.pdf

### [GANS (II)](https://github.com/AntNLP/seminar/tree/master/2016Fall/GANs%20(II))
- Slides
  - Slides-2016-12-04-NIPS.pdf

## clab/dynet
- Slides
	- dyer-goldberg-neubig-t1.pdf
	- dyer-goldberg-neubig-t1b.pdf
- Ref
	- [github](https://github.com/clab/dynet)
	- [document](http://dynet.readthedocs.io/en/latest/index.html)
	- [tuturial code](https://github.com/clab/dynet_tutorial_examples)