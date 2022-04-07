# Topic-Noise Models Source
This repository contains Mallet implementations of topic-noise models (and a stripped-down version of the original Mallet LDA), used in the Georgetown DataLab Topic Modeling (`gdtm`) [Python package](https://github.com/GU-DataLab/gdtm).  Many thanks to Andrew McCallum, David Mimno, and the other Mallet contributors for creating such fast and accurate topic models for us to base our implementations on.

These models are intended to be used in conjunction with the `gdtm` Python package for topic models, but can also be used standalone, in the same manner as the original [Mallet package](http://mallet.cs.umass.edu).

### Contents
***

#### Mallet-LDA
A stripped-down version of the original Mallet package that contains LDA.
***
#### Mallet-TND
Mallet implementation of Topic-Noise Discriminator
***
#### Mallet-eTND
Mallet implementation of embedded Topic-Noise Discriminator.  Use this if you plan on enhancing the noise distribution of TND with word embedding sampling.
***
#### Mallet-GTM
Mallet implementation of Guided Topic-Noise Model.  This contains only the generative seeding model.  The rest of GTM is implemented in Python, as it is an ensemble of the seeding model and TND.
***
#### Mallet-DTND
Mallet implementation of Dynamic Topic-Noise Discriminator (temporal topic-noise model).
***
#### Mallet-DeTND
Mallet implementation of Dynamic embedded Topic-Noise Discriminator (temporal embedded topic-noise model).  Use if you plan on enhancing the temporal version of TND with word embedding sampling.
***
#### Mallet-DLDA
Mallet implementation of dynamic LDA, a.k.a. dynamic topic models (DTM).
***

### References
1. A. K. McCallum, “Mallet: A machine learning for language toolkit.” 2002.
2. David M. Blei, Andrew Y. Ng, and Michael I. Jordan. "Latent dirichlet allocation." Journal of Machine Learning Research, 3:993–1022, 3 2003.
3. David M Blei and John D Lafferty. "Dynamic topic models." In: International Conference on Machine Learning (ICML), pages 113–120, 2006.
4. R. Churchill, L. Singh, "Percolation-based topic modeling for tweets." In: KDD Workshop on Issues of Sentiment Discovery and Opinion Mining (WISDOM). 2020.  
5. R. Churchill, L. Singh, "Topic-noise models: Modeling topic and noise distributions in social media post collections." In: International Conference on Data Mining (ICDM). 2021.  
6. R. Churchill, L. Singh, "Dynamic Topic-Noise Models for Social Media." In: Pacific-Asia Conference on Knowledge Discovery
and Data Mining (PAKDD). 2022.  
7. R. Churchill, L. Singh, "A Guided Topic-Noise Model for Short Texts." In: The Web Conference (WWW). 2022.
