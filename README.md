<h1 align="center">Brain tumor detection</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/anuragdaksh7/brain-tumor)](https://github.com/anuragdaksh7/brain-tumor/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/anuragdaksh7/brain-tumor)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>


---

## 🧐 About <a name = "about"></a>

A Convolution Neural Network based model which categorize given MRI into 4 classes which are 'glioma', 'meningioma', 'notumor', 'pituitary' with over 94% validation/ test accuracy. The dataset was picked from [KAGGLE](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset) which has approx 1400 images per class of training data, each image itself is a 512x512 px image which is enough for our project.<br/>

Our model consists of convolutional layers to extract spatial features, pooling layers to reduce dimensionality, and fully connected layers for classification. The model is suitable for tasks like object recognition, scene classification, and medical image analysis

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them.

```
python (The code is used on Python 3.12.4)
jupyter notebook (pip install notebook)
```

### Installing
- First clone the repository and install the dataset from the link mentioned in the about section.

```
pip install -r requirements.txt
```

now launch jupyter notebook in the current directory

```
jupyter notebook
```
- After installing everything, update the relative path of dataset in the brain-tumor.ipynb file

## References
- [Brain Tumor Segmentation in MRI Images with 3D U-Net and Contextual Transformer](https://arxiv.org/pdf/2407.08470)
- [BRAIN TUMOR CLASSIFICATION FROM MRI IMAGES USING MACHINE LEARNING](https://arxiv.org/pdf/2407.10630)
- [Deep Learning in Medical Image Classification from MRI-based Brain Tumor Images](https://arxiv.org/pdf/2408.00636)


## ⛏️ Built Using <a name = "built_using"></a>

- [Python](https://python.org/) - Python
- [Jupyter Notebook](https://jupyter.org/) - Runtime
- [Tensorflow](https://www.tensorflow.org/) - AI Framework
- [Kaggle](https://www.kaggle.com//) - Dataset Access

## ✍️ Authors <a name = "authors"></a>

- [@anuragdaksh7](https://github.com/anuragdaksh7)
