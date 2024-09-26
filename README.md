# Training a CNN to classify peripheral blood cell images 

## Introduction
introduction goes here

## Prerequisites

- **Software:**
  - Google collab
  - kaggle account

## Step 1: Upload your Kaggle API key 

### 1.1 import the key
   ```bash
   from google.colab import files
   files.upload()
   ```
### 1.2 Download the dataset using the Kaggle API:
  
   ```bash
   !mkdir -p ~/.kaggle
   !cp kaggle.json ~/.kaggle/
   !chmod 600 ~/.kaggle/kaggle.json
  
   !kaggle datasets download -d kylewang1999/pbc-dataset
   ```

### 1.3 Unzip the dataset:
   ```bash
   !unzip pbc-dataset.zip
   ```
*TEST_ITALICS*
**TEST_BOLD**
<kbd>TEST_FORMAT</kbd> 
