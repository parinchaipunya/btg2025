# README

## Cloning the repo to your google drive.

Put the following two blocks into your colab notebook.
The folder will be located at `/content/drive/MyDrive/bth2025`
```
from google.colab import drive
drive.mount('/content/drive')
```
```
%%bash
cd /content/drive/MyDrive/
git clone https://github.com/parinchaipunya/btg2025.git
```
