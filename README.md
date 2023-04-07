# Bottlenecks CLUB

The official code of "**Bottlenecks CLUB: Unifying Information-Theoretic Trade-offs among Complexity, Leakage, and Utility**", IEEE Transactions on Information Forensics and Security, 2023. [[arXiv](https://arxiv.org/abs/2207.04895)].

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
* Run exp_colored_mnist_P3.ipynb for Colored-MNIST experiments with the Algorithm P3 supervised or unsupervised version

* Run exp_celeba_P1.ipynb for CelebA experiments with the Algorithm P1 supervised or unsupervised version
* Run exp_celeba_P3.ipynb for CelebA experiments with the Algorithm P3 supervised or unsupervised version

* **Note:** There is a Boolean config variable (called _supervised_) at the beginning of each experiment for changing algorithm type to the supervised or unsupervised type
## Help

It is highly recommended to select the appropriate batch size based on your GPU's memory and computer specification to utilize maximum efficiency on your computer. 

## Authors

* Behrooz Razeghi
* Amir Atashin

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Citation

```
@article{razeghi2023BottlenecksCLUB,
  author={Razeghi, Behrooz and Calmon, Flavio P. and Gunduz, Deniz and Voloshynovskiy, Slava},
  journal={IEEE Transactions on Information Forensics and Security}, 
  title={Bottlenecks CLUB: Unifying Information-Theoretic Trade-Offs Among Complexity, Leakage, and Utility}, 
  year={2023},
  volume={18},
  number={},
  pages={2060-2075},
  doi={10.1109/TIFS.2023.3262112}}
```

## Acknowledgments

Inspiration, code snippets, etc.
* [download CelebA dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)
