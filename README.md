# CNNs Project

This project aims to automatically categorize products based on their images using a deep learning model. The dataset used in this project is provided by Torob, a shopping search engine that aggregates product information from various online stores. By doing so, users can easily search for products and compare different sellers in a single interface.

## Project Overview

The key objective of this project is to build a Convolutional Neural Network (CNN) model capable of classifying products into appropriate categories based on product images. In a platform like Torob, accurate product categorization is crucial for improving the searchability and comparison of products, making it easier for users to find what they are looking for.

## Motivation

Manually refining and extracting information from such a large volume of data is time-consuming and costly. Automated product information recognition, particularly product categorization, plays a vital role in addressing this challenge.

## Model Architecture

The project leverages Convolutional Neural Networks (CNNs), a class of deep neural networks, particularly well-suited for image classification tasks. The following steps are taken to design the model:
- **Data Preprocessing**: Preprocessing the dataset to normalize images and prepare them for input into the CNN model.
- **Constructing Model Using Transfer Learning**: Using transfer learing in order to take advantage of the ResNet model arcitecture with self-built prediction head (FNN head) and trai
- **Evaluation metrics and performance analysis**: The model is evaluated based on accuracy score to ensure the performance meets the project requirements.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/alirezamirrokni/CNNs-project.git
    cd CNNs-project
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Prepare the dataset:
    - Download the dataset (not included in the repository).
    - Preprocess the images and organize them into the required folder structure.

4. Train the model:
    ```bash
    python train.py --dataset path_to_dataset --epochs 50
    ```

5. Evaluate the model:
    ```bash
    python evaluate.py --model path_to_trained_model --dataset path_to_validation_dataset
    ```

## Results

The results of the trained model, including its accuracy and performance on various product categories, will be displayed during the evaluation phase. Further details on the results can be found in the results folder.

## Contributions

Contributions are welcome! Please fork this repository and submit a pull request for any features, fixes, or enhancements you’d like to see.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
