# Convolutional_Networks_reterpret
This project aims to reproduce the results of the paper "Visualizing and Understanding Convolutional Networks" by Matthew D. Zeiler and Rob Fergus, and extend their work by applying their visualization technique to the CIFAR-10 dataset.


## Data
we used CIFAR-10. It consists of 60,000 color images categorized into 10 different classes.

## Requirements
This project was developed using Google Colab. To run the code, you will need:
* Python 3.6 or later
* PyTorch 1.0 or later
* torchvision
* matplotlib
* numpy

 ```sh
pip install torch torchvision matplotlib numpy
  ```
If you are using a Jupyter notebook
 ```sh
 !pip install torch torchvision matplotlib numpy
  ```
  ## Project Structure
  The entire project is contained within a single Jupyter notebook: 'main.ipynb'. This notebook includes all the steps from data loading, preprocessing, model training, evaluation, and results visualization for the feature mapping.

## Models
| Model name | Accuracy |
|------------|----------|
| model_1| (0.85) |
| model_2 | (0.75) |
## method
* feature mapping using using a `Deconvolutional` Network

## Contributing
### Authors
- [Qatrlnada Almrzoq]()
- [Feda Alashwal]()


## References
* `Deconvolutional`: [Visualizing and Understanding Convolutional Networks, Matthew D Zeiler et al. 2014](https://arxiv.org/abs/1311.2901)
