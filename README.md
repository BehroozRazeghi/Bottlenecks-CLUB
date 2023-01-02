# CLUB

This is a repository of the code for "Bottlenecks CLUB: Unifying Information-Theoretic Trade-offs among Complexity, Leakage, and Utility".

## Getting Started

### Dependencies

* Python 3.7+
* TensorFlow 2.4.1
* Pandas
* Matplotlib (for graphs and figures)
* OpenCV-python (to read and preprocess image data in CelebA experiments)

### Installing

* Download repository
* Install Dependencies
* Download [img_align_celeba.zip](https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg) and extract it to the CelebA folder in the root of the project

### Executing program

* Run data_colored_mnist.ipynb to generate Colored-MNIST dataset (both biased and uniform)

* Run exp_colored_mnist_P1.ipynb for Colored-MNIST experiments with the Algorithm P1 supervised or unsupervised version
* Run exp_colored_mnist_P5.ipynb for Colored-MNIST experiments with the Algorithm P3 supervised or unsupervised version

* Run exp_celeba_P1.ipynb for CelebA experiments with the Algorithm P1 supervised or unsupervised version
* Run exp_celeba_P5.ipynb for CelebA experiments with the Algorithm P3 supervised or unsupervised version

* **Note:** There is a Boolean config variable (called _supervised_) at the beginning of each experiment for changing algorithm type to the supervised or unsupervised type
## Help

It is highly recommended to select the appropriate batch size based on your GPU's memory and computer specification to utilize maximum efficiency on your computer. 

## Authors

* Amir Atashin
* Behrooz Razeghi

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Citation
@article{razeghi2022bottlenecks,
  title={Bottlenecks CLUB: Unifying Information-Theoretic Trade-offs Among Complexity, Leakage, and Utility},
  author={Razeghi, Behrooz and Calmon, Flavio P and Gunduz, Deniz and Voloshynovskiy, Slava},
  journal={arXiv preprint arXiv:2207.04895},
  year={2022}
}


## Acknowledgments

Inspiration, code snippets, etc.
* [download CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
