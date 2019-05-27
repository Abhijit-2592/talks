# talks

Accompanying codes for various presentations. Mostly contains interactive Jupyter Notebooks to accompany the slides.

## Installation:

**NOTE:** All the examples use `python-3.6`. This project uses `git-lfs` to track images and other binaries. So install `git-lfs` before cloning the repository

1.  Run `curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash`
2.  Run `sudo apt install git-lfs`
3.  Run `git clone https://github.com/Abhijit-2592/talks.git`
3.  Install requirements using `pip install -r requirements.txt`
4.  Install `keras-vis` again using `pip install git+https://github.com/raghakot/keras-vis.git -U`. The pip version has a bug which was fixed in source but was not exported as a pip wheel.

## Contents:

-   [cnn_vis](./cnn_vis): Self contained Jupyter Notebooks and images which try to visualize what CNNs learn. Also contains a [notebook](./cnn_vis/fooling_cnns.ipynb) which explains how fool CNNs
-   [requirements.txt](./requirements.txt): `pip` requirements to run the notebooks.

## Talks:

### Talk 1:
-  Topic:   `Visualizaing and understanding what Convolutional Neural Networks Learn!`
-  Venue:   [SRM Institute of Science and Technology](http://www.srmuniv.ac.in/)
-  [Slides](https://docs.google.com/presentation/d/1rg_j2bZijLYuOShWXiA0Sk0LU1oJwQ3hyDC6EtzpizE/edit?usp=sharing)
-  Codes: [cnn_vis](./cnn_vis)

**References:**
-   Most of the slide materials are adopted from [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/). Specifially, [Lecture 9](http://cs231n.stanford.edu/slides/2016/winter1516_lecture9.pdf) from **2016**. I have tried my best to replicate few visualizations in code which [Andrej Karpathy](https://cs.stanford.edu/people/karpathy/) mentions in his lecture.
-   Saliency map and Activation maximization visualizations are adopted from [keras-vis](https://github.com/raghakot/keras-vis)
