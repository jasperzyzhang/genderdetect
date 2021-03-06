# Gender Detection from Facial Images with and without Mask
### Update

August 7th: visualization function for Loss and Accuracy added.

### Author

* Soo Woon (Shawn) Chung
* Jingwen (Rebecca) Du
* Jingxian (Phebe) Lan
* Zhongyuan (Jasper) Zhang

### Introduction

Here is a collection of code and datasets corresponding to our project "Gender Detection from Facial Images with and without Mask".



Due to size limit, The Google Shared Folder https://drive.google.com/drive/folders/14a38EqwCzzJNp3faOuxFNfnFgyEW-hPO?usp=sharing includes the following files:

**Datasets**: CelebA, Casia WebFace Facial, Google Crawled

**Best Model's Weight** :weights6.best.inc.male.hdf5

Otherwise, all required files are stored in the github repository.

Before training the model, Unzip datasets in to `imgs/` folder.

### Requirements

- python==3.7
- tensorflow==2.0
- keras==2.3.1
- matplotlib==3.3.0
- opencv-python==4.3.0

The directory structure is as follows:
```
genderdetect/

	|-> main.py/				* changing hyperparameters and set folder path
	|-> load_attr.py			* Load image info
	|-> training.py		       		* network structures, train/test functions
	|-> generate.py				* data preprocessing and loading
	|-> plot.py				* results visualization

```

We also provide a notebookfile 7. DLPROJECT2-TestCutout_5squares_size30.ipynb containing the entire data preprocessing, training, validation, testing steps for convenience.

