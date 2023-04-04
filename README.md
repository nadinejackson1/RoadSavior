# RoadSavior 🚧

RoadSavior is a deep learning-based road segmentation project aimed at extracting accurate road networks from aerial images to assist in crisis response efforts, such as search and rescue missions.🚑🚁

### The Journey 🌄

Our world is no stranger to natural disasters and catastrophes. In these critical moments, every second counts. Having accurate maps of road networks can make the difference between life and death. Unfortunately, not all regions have detailed maps, and rapidly changing landscapes due to disasters further complicate matters.

This is where the RoadSavior project comes in! By leveraging the power of AI, I wanted to find a way to provide a helping hand to rescue teams and crisis responders, equipping them with the most up-to-date road data. 🌐🌪️

### The Power of Deep Learning 🧠

RoadSavior harnesses the potential of deep learning models to segment roads from satellite images with remarkable precision (model achieved a training accuracy of 97.56% and a validation accuracy of 97.09%). This project uses the state-of-the-art U-Net architecture, trained on the DeepGlobe Road Extraction Challenge dataset. This neural network delves into the depths of aerial images, extracting road networks that are crucial for navigating disaster zones.🛰️🛣️

# Get Started 🚀

### Requirements

- Cuda 8.0
- Python 2.7
- Pytorch 0.2.0
- cv2

### Usage

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

