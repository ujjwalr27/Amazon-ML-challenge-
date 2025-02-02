# Amazon ML Challenge - Product Information Extraction

## Project Overview
This project is part of the Amazon ML Challenge, focusing on extracting structured information from product images. The goal is to develop a machine learning model that can accurately extract various product attributes (like dimensions, weight, etc.) from product images and their associated text.

## Dataset Description
The project uses the following datasets:
- `train.csv` (21.5 MB): Training dataset containing labeled data
- `test.csv` (9.8 MB): Test dataset for model validation
- `finaltest.csv` (24.4 MB): Final test dataset for evaluation
- `dataset.csv` (3.4 MB): Additional dataset

The data includes the following key features:
- `image_link`: URL to the product image
- `group_id`: Identifier for grouping related products
- `entity_name`: Type of product attribute (e.g., height, width, weight)
- `textfromimg`: Extracted text from the product image

## Implementation
The implementation is done in Python using Jupyter Notebook (`sourcecode.ipynb`). Key libraries used include:
- pandas: For data manipulation and analysis
- numpy: For numerical operations
- tqdm: For progress tracking
- Regular expressions (re): For text processing

## Model Approach
The solution involves:
1. Data preprocessing and cleaning
2. Text extraction from images
3. Entity recognition for product attributes
4. Structured information extraction

## Getting Started
1. Install the required dependencies
2. Load the datasets
3. Run the Jupyter notebook `sourcecode.ipynb`

## File Structure
```
.
├── README.md
├── dataset.csv
├── finaltest.csv
├── sourcecode.ipynb
├── test.csv
└── train.csv
