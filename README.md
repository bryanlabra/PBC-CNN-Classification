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
  You can replace the dataset by substituting the last line. You can find the exact command by clicking on the arrow to the right of the download button and selecting **COPY API COMMAND**
  <img width="1405" alt="Screenshot 2024-09-26 at 2 58 11 PM" src="https://github.com/user-attachments/assets/032af63c-a393-4350-9847-9ef624d4f843">
  
### 1.3 Unzip the dataset:
   ```bash
   !unzip pbc-dataset.zip
   ```
## Step 2: Upload your Kaggle API key 




*TEST_ITALICS*

**TEST_BOLD**

<kbd>TEST_FORMAT</kbd> 
