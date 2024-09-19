# CNNs Project

This project aims to automatically categorize products based on their images using a deep learning model. The dataset used in this project is provided by Torob, a shopping search engine that aggregates product information from various online stores. By doing so, users can easily search for products and compare different sellers in a single interface.

## Project Overview

The key objective of this project is to build a Convolutional Neural Network (CNN) model capable of classifying products into appropriate categories based on product images. In a platform like Torob, accurate product categorization is crucial for improving the searchability and comparison of products, making it easier for users to find what they are looking for.

## Motivation

Manually refining and extracting information from such a large volume of data is time-consuming and costly. Automated product information recognition, particularly product categorization, plays a vital role in addressing this challenge.

## Model Architecture

The project leverages Convolutional Neural Networks (CNNs), a class of deep neural networks, particularly well-suited for image classification tasks. The following steps are taken to design the model:
- **Data Preprocessing**: Preprocessing the dataset to normalize images and prepare them for input into the CNN model.
- **Constructing Model (Using Transfer Learning)**: Using transfer learing in order to take advantage of the ResNet model arcitecture with self-built prediction head (FNN head).
- **Evaluation metrics and performance analysis**: The model is evaluated based on accuracy score to ensure the performance meets the project requirements.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: tensorflow, keras, numPy, pandas, matplotlib, glob

Install the dependencies using:

```bash
pip install -r requirements.txt
```
## Usage

1. **Clone the repository**:

    ```bash
    git clone https://github.com/alirezamirrokni/CNNs-project.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd CNNs-project
    ```
    
3. **Open `.ipynb` file and run its cells**.

## Results

- ROC_AUC score for the first part on validation set:

    [![part1.png](https://i.postimg.cc/BQqk3Qww/part1.png)](https://postimg.cc/5jRnq1Jw)

- Accuracy score for the second part on validation set:

    [![part2.png](https://i.postimg.cc/BZ5kR1NK/part2.png)](https://postimg.cc/grJgZjCz)

## Authors        
-[Alireza Mirrokni](https://github.com/alirezamirrokni)    
