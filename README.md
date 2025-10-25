# Mini Project 1 - NSSP

This repository contains all the code related to the Mini Project 1 for the course "Neural Signals and Signal Processing".

## Dataset Installation

To install the dataset in the correct position, follow the next steps:

### 1. Make Sure the NX-421 Conda Environment is active and you are in the root of this project
```
conda activate NX-421
cd .../nssp-mp1
mkdir dataset
```

### 2. Install Gdown Python Library from pip
```
pip install gdown
```

### 3. Run the command
```
gdown --folder https://drive.google.com/drive/folders/1oBqhHXK-NYG0Cjw8MfmN3_0yYV4gqaUa -O dataset/subject101410
```

## Important
The folder "dataset" and the "Preprocessing.py" file have to be on the same directory