# Food101 Classification with EfficientNetB2 in PyTorch

## Introduction
This project applies transfer learning techniques using the EfficientNetB2 model to classify images from the Food101 dataset. The goal is to accurately identify different food categories using a pre-trained neural network fine-tuned on Food101 dataset.

## Dataset
The Food101 dataset consists of 101 food categories, with 101,000 images. For each class, 250 manually reviewed test images are provided as well as 750 training images. More details can be found here.

## Model
EfficientNetB2 is a convolutional neural network that is both highly efficient and effective, scaling up to achieve state-of-the-art accuracy on a variety of datasets. More details about EfficientNet can be found in the original paper.

## Requirements

- torch==2.1.2
- torchvision==0.16.2
- tqdm==4.66.1
- matplotlib==3.7.5
- numpy==1.26.4
- pandas==2.2.0
- sklearn==1.2.2
- torchinfo==1.8.0


## Usage
1. Clone the repository: 
```
git clone https://github.com/henrythdu/Food-Vision-Big.git
```

2. Install the dependencies:

```python
pip install -r requirements.txt
```

3. Run the training notebook:
```
FoodVisionBig_training.ipynb
```

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Food101 dataset creators
- Original authors of the EfficientNet model
