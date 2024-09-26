# Interfacing Raspberry Pi Zero 2 W with Arducam Module 3 and 1.14" LCD module

## Introduction

This repo will serve as a step-by-step guide on how to interface a raspberry pi zero 2 w with a Arducam module 3 (IMX708 sensor), a 1.14" LCD display screen (ST7789 Driver), and a board-mounted tactile switch (or any switch for that matter).

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
