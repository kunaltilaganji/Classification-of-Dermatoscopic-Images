# Skin Cancer Lesion Classification using HAM10000 Dataset

This is a Skin Cancer Lesion Classification project.In this repository, I tackle the task of classifying dermatoscopic images into different categories of skin cancer lesions using the HAM10000 dataset. Skin cancer is a significant health concern, and early detection through image analysis can be a powerful tool in aiding diagnosis.

## Dataset Overview

The [HAM10000 dataset Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000) is a collection of dermatoscopic images of skin lesions, containing seven classes of skin cancer lesions:

## Skin Cancer Lesion Classes

| Class                               | Description                                                                                                  |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Melanocytic nevi (nv)               | Melanocytic nevi, also known as moles, are benign skin lesions consisting of melanocytes.                   |
| Melanoma (mel)                      | Melanoma is a malignant skin cancer that arises from melanocytes. It is the most dangerous form of skin cancer. |
| Benign keratosis-like lesions (bkl) | Benign keratosis-like lesions include various non-cancerous skin conditions that resemble actinic keratoses or basal cell carcinomas. |
| Basal cell carcinoma (bcc)          | Basal cell carcinoma is a common form of skin cancer that arises from basal cells in the epidermis.           |
| Actinic keratoses (akiec)           | Actinic keratoses, also known as solar keratoses, are precancerous lesions caused by sun exposure.             |
| Vascular lesions (vas)              | Vascular lesions include various blood vessel-related skin conditions, such as angiomas.                    |
| Dermatofibroma (df)                 | Dermatofibroma is a benign skin condition characterized by fibrous tissue growth in the dermis.               |


## Project Structure

- `data/`: Placeholder for the dataset (not included in the repository).
- `models/`: Trained machine learning models.
- `src/`: Source code for data preprocessing, model training, and evaluation. All Jupyter files.
- `requirements.txt`: List of project dependencies.
- `README.md`: This file.

## Getting Started

1. **Installing Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

2. **Download and Prepare Dataset:**

   - Download the HAM10000 dataset from [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000).
   - Extract the dataset files into the `data/` directory.
   - Run data preprocessing scripts in the `src/` directory to prepare the dataset.


![Dataset Stats](https://github.com/kunaltilaganji/Classification-of-Dermatoscopic-Images/blob/main/images/Graph%20of%20Loss%20and%20Accuracy.png)  

4. **Exploration and Model Training:**

   Explore the Jupyter notebooks in the `notebooks/` directory for data analysis and model training.

5. **Evaluate Models:**

   You can evaluate the trained models using the provided scripts in the `src/` directory.



## Acknowledgments

- [HAM10000 Dataset](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
- [Original Research paper](https://arxiv.org/ftp/arxiv/papers/1803/1803.10417.pdf)
- [Digital Sreeni](https://www.linkedin.com/in/digitalsreeni)


Thank you for your interest in our project!

