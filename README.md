# DCGAN Face Generation

A DCGAN is trained on a dataset of faces. A generator network generates new images of faces that look very realistic. The DCGAN utilizes 64 convolutions for both the discriminator and generator starting point.

## Installation

1. Clone this repository into directory under running Jupyter notebook instance:

   `git clone git@github.com:rigganni/DCGAN-Face-Generation.git`

2. Ensure the necessary Python environment is set up. See the Anaconda environment file `conda.yml` in this repository. The environment can be created by the following:

   `conda env create -f conda.yml`


## Files

* `dcgan_face_generation.ipynb`: Jupyter notebook containing all code to create DCGAN
* `problem_unittests.py`: Unit tests to check if DCGAN set up correctly
* `train_samples.pkl`: Training samples to visualize once training completes
* `conda.yml`: Anaconda enivronment file to reproduce development environment


## Usage

Run the Jupyter notebook `dcgan_face_generation.ipynb`.

## Future Improvements

* Run additional epochs to reduce blurriness
* Stop and/orstore the model then the Generator is at a lower loss than the best previous epoch loss
* Obtain a more diverse dataset that is more representative of all human faces
