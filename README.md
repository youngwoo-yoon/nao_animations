# NAO Animations
This project, done with the permission of the [Electronics and Telecommunications Research Institute of Korea](http://etri.re.kr/), seeks to generate intelligent, adaptive behavioral gestures in the Aldebaran NAO robot. 

## Overview
Recent developments in machine learning, natural language processing, and computer vision have spurred research in intelligent robotics. We aim to make robots more believable in their behavior, and in working with NAO, we hope to generate synchronous, distinct body language taken not from a predetermined set of gestures, but adapted and learned methodically from sensor data and textual analysis.

### Methods
Working with `anaconda`, we utilize several libraries such as `spacy`, `seaborn`, `naoqi`, and `scikit-learn`. Speech analysis is done in `spacy`, a robust NLP library with significant performance advantages over other popular libraries such as `nltk`. `scikit-learn` is the base for all machine learning tasks. Data is taken from NAO's joint sensors and viewed with `seaborn`, then extrapolated through uniform random, but statistically significant values to generate new motions.

All scripts are specced accordingly (by functions and operations) and are best viewed in `pycharm` for documentation purposes.

### References
Some useful papers resourced for the project include, but are not limited to, the following:

* [Model of expressive gestures for humanoid robot NAO
](http://pages.isir.upmc.fr/~achard/GdR/p2.pdf)
* [Gesture generation with low-dimensional embeddings](http://ict.usc.edu/pubs/Gesture%20generation%20with%20low-dimensional%20embeddings.pdf).
 