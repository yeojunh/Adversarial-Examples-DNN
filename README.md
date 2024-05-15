[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Noise in the Network: Comparing Defence Methods for Adversarial Examples in Neural Networks
Final project for [CPSC 440/550 2023W2 Advanced Machine Learning](https://www.cs.ubc.ca/~dsuth/440/23w2/) course taught by [Danica J. Sutherland](https://djsutherland.ml/) at the University of British Columbia, Vancouver. 


# Abstract 
This paper explores the vulnerability of Convolutional Neural Networks (CNNs) and Deep Neural Networks (DNNs) to adversarial attacks using CIFAR-10 images. It evaluates the performance of adversarial training methods, revealing that while the original ResNet50 model performs best on unaltered data, it struggles with adversarial attacks. Ensemble adversarial training, which uses adversarial examples designed against other pre-trained models, shows improved robustness but slightly lower performance on standard classification tasks. Future work aims to expand the range of adversarial examples, explore different image classification models, and incorporate a wider array of defense mechanisms. The findings show an improved robustness of defense mechanisms even with small underfit models and this study overall will inform strategies to better defend DNNs from adversarial attacks.

More details on the project are on the [Project Proposal](CPSC_440_Project_Proposal.pdf) and [Final Project Report](CPSC_440_Final_Project_Report) in this repository.

# Getting Started

1. Clone the repo 
```
git clone https://github.com/yeojunh/CPSC440-project.git
```

2. Run the [project notebook](cpsc440_project.ipynb) on a Python environment of choice. I personally used Google Colab, but Anaconda or any other environment that uses Python Notebooks should work. Ensure that all the required dependencies are properly installed: 
```
pip install numpy
pip install tensorflow
pip install torch
pip install torchvision
pip install matplotlib
pip install random
pip install pickle
pip install cleverhans
```

# Contact
Yeojun Han - [yeojun.com](https://yeojun.com) - yeojunh [at] student.ubc.ca

Project Link: https://github.com/yeojunh/Noise-in-the-Network

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/yeojun
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/yeojunh/CPSC440-project/license.txt
