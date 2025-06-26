# README

## Cloning the repo to your google drive.

- Import gdrive to colab.
```
from google.colab import drive
drive.mount('/content/drive')
```

- Clone.
```
%%bash
cd /content/drive/MyDrive/
mkdir -p deep-learning-for-coders
cd deep-learning-for-coders
git clone https://github.com/fastai/course22.git
```
