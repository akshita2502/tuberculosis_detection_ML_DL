# Tuberculosis Detection using ML/DL on Chest X-Ray Images

This project applies deep learning and machine learning techniques to detect tuberculosis from chest X-ray images using feature extraction and classification.

## Features

- Feature extraction using VGG19, ResNet101, and DenseNet201 (pre-trained on ImageNet)
- Classification using XGBoost
- Evaluation metrics and visualization (confusion matrix, loss curves)
- Works with two datasets: TB Chest Radiography Database and Shenzhen Database

## Prerequisites

- Python 3.8+
- Google Colab or local Jupyter environment
- Download datasets and place them in the specified folders

## Installation

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the notebooks:
   - `Tuberculosis CXR Database.ipynb`
   - `Shenzhen Database.ipynb`
2. Mount Google Drive if using Colab and set correct dataset paths.
3. Run all cells sequentially:
   - Load and preprocess data
   - Extract features using VGG19, ResNet101, DenseNet201
   - Save extracted features to Excel files
   - Train and evaluate XGBoost classifiers
   - Visualize results

## Project Structure

- `requirements.txt` — Python dependencies
- `README.md` — Project description and instructions
- `Tuberculosis CXR Database.ipynb` — Notebook for TB Chest Radiography Database
- `Shenzhen Database.ipynb` — Notebook for Shenzhen Database

## Results

- Feature files saved as Excel sheets
- Classification metrics and plots for each model

## License

This project is for academic use only.
