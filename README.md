# Mini Project 1 - NSSP

This repository contains all the code related to the Mini Project 1 for the course "Neural Signals and Signal Processing".

## Dataset Installation

To install the dataset in the correct position, follow the next steps:

### 1. Conda environment and create directory
Ensure your `NX-421` Conda environment is active and you are in the root directory of this project (nssp-mp1).

```
conda activate NX-421
cd path/to/nssp-mp1
mkdir dataset
```

### 2. Install Gdown
Install the gdown Python library using pip to facilitate downloading files from Google Drive.

```
pip install gdown
```

### 3. Download the dataset
Run the following command to download the data for `subject101410` into the newly created `dataset/` folder.

```
gdown --folder https://drive.google.com/drive/folders/1oBqhHXK-NYG0Cjw8MfmN3_0yYV4gqaUa -O dataset/subject101410
```

## Important
The folder "dataset" and the "Preprocessing.py" file have to be on the same directory
