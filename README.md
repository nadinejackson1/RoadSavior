# DeepGlobe-Road-Extraction-Challenge
Code for the 1st place solution in [DeepGlobe Road Extraction Challenge](https://competitions.codalab.org/competitions/18467).

# Requirements

- Cuda 8.0
- Python 2.7
- Pytorch 0.2.0
- cv2

# Usage

### Data
Place '*train*', '*valid*' and '*test*' data folders in the '*dataset*' folder.

Data is from [DeepGlobe Road Extraction Challenge](https://competitions.codalab.org/competitions/18467#participate-get_starting_kit). You should sign in first to get the data.

### Train
- Run `python train.py` to train the default D-LinkNet34.

### Predict
- Run `python test.py` to predict on the default D-LinkNet34.

### Download trained D-LinkNet34
- [Dropbox](https://www.dropbox.com/sh/h62vr320eiy57tt/AAB5Tm43-efmtYzW_GFyUCfma?dl=0)
- [百度网盘](https://pan.baidu.com/s/1wqyOEkw5o0bzbuj7gBMesQ)

# RoadSavior 🚧

RoadSavior is a deep learning-based road segmentation project aimed at extracting accurate road networks from aerial images to assist in crisis response efforts. Our mission is to empower emergency response teams by providing them with precise road information, enabling them to save lives in the most challenging situations. 🚑🚁

### The Journey 🌄

Our world is no stranger to natural disasters and catastrophes. In these critical moments, every second counts. Having accurate maps of road networks can make the difference between life and death. Unfortunately, not all regions have detailed maps, and rapidly changing landscapes due to disasters further complicate matters.

This is where RoadSavior comes in! By leveraging the power of AI, we aim to provide a helping hand to rescue teams and crisis responders, equipping them with the most up-to-date road data. 🌐🌪️

### The Power of Deep Learning 🧠

We've harnessed the potential of deep learning models to segment roads from satellite images with remarkable precision. Our project uses the state-of-the-art U-Net architecture, trained on the DeepGlobe Road Extraction Challenge dataset. This neural network delves into the depths of aerial images, extracting road networks that are crucial for navigating disaster zones. 🛰️🛣️

### How to Contribute 💡

Passion and collaboration fuel RoadSavior. We're always looking for enthusiastic contributors who share our vision to save lives and make a difference. Whether you're a deep learning wizard, a GIS expert, or just someone eager to help, we welcome your contributions!

- Share ideas for model improvements
- Suggest new data sources
- Optimize our code
- Spread the word about RoadSavior

Together, we can build an invaluable tool for crisis response efforts and make a lasting impact on the world. 🌟🤝

### Get Started 🚀

Follow the step-by-step guide in the Jupyter Notebook to train your very own road segmentation model. Dive into the world of deep learning and join our quest to revolutionize crisis response with AI.

Ready to embark on this life-saving journey? Clone our repo and become a part of the RoadSavior community! 💖

    git clone https://github.com/nadinejackson1/RoadSavior.git

_"Mapping roads for a safer world, one pixel at a time!"_ 🌍💖
