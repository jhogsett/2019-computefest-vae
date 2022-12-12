# 2019-computefest-vae
Variational Auto Encoder Sample - Revived - 12-12-2022

Sample from: https://github.com/Harvard-IACS/2019-computefest/tree/master/Wednesday/auto_encoder

I had to make a few changes to run the notebook (marked JH)

Their website and YouTube video
* https://www.computefest.seas.harvard.edu/past-events#:~:text=HANDS%2DON%20WORKSHOP-,ComputeFest%202019,-SYMPOSIUM%20%2D%C2%A0DATA%20SCIENCE
* https://www.youtube.com/watch?v=YMC-dehNLBE
* CelebA dataset https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

## My Setup
* Windows 10
* RTX 2080 Ti GPU
* Anaconda / Jupyter Notebook
* Python 3.9.15
* CUDA 11.7

## My Observations

* I was able to both train and generate using both MNIST examples
* I could train the Celeba example, at least the shortened training in the notebook, but I always got black generated images
    * Loading the pre-trained model allowed me to use the rest of the sample
    * I don't know if the black images are due to needing to train the whole set of faces, or if there is a problem/incompatibility in the original code
