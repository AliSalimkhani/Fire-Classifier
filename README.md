# KNN Image Classifier

Welcome to the **KNN Image Classifier** project! This repository demonstrates a simple yet effective implementation of a K-Nearest Neighbors (KNN) model for image classification. With an accuracy of **86.5%**, this project is a great starting point for understanding and utilizing KNN for image-based machine learning tasks.

## File Structure
This project includes:
- `knn-image-classification.ipynb`: Core notebook for training and saving the KNN model.
- `Client.ipynb`: Client notebook for using the pre-trained model.
- `fire_classifier.z`: Serialized KNN model for image classification.
- `test`: A folder containing a few sample photos for manually testing the model. You can add more images to this folder.
  

1. **The Core Project Notebook:**
   - File: `knn-image-classification.ipynb`
   - This Jupyter Notebook contains the implementation of the KNN model, data preprocessing and training steps. It also includes the process of saving the trained model as `fire_classifier.z` for external use.

2. **The Client Version Notebook:**
   - File: `Client.ipynb`
   - A simplified notebook designed for end-users who want to use the pre-trained KNN model (`fire_classifier.z`) to classify images without diving into the training process.

3. **Pre-Trained Model:**
   - File: `fire_classifier.z`
   - The trained KNN model serialized for easy distribution and use in client applications.

## Getting Started

### Prerequisites
To run the notebooks, make sure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries (install them using the command below):

```bash
pip install scikit-learn
pip install opencv-python
pip install glob
pip install joblib
```

### Running the Core Project
1. Open the `knn-image-classification.ipynb` notebook in Jupyter.
2. Download the Dataset from [here](https://www.kaggle.com/datasets/phylake1337/fire-dataset).
3. Follow the cells to explore data preprocessing and training of the KNN model.
4. The notebook will generate and save the `fire_classifier.z` model for client usage.

### Using the Client Version
1. Open the `Client.ipynb` notebook in Jupyter.
2. Download the pre-trained model (`fire_classifier.z`) and place it in the same directory as the notebook.
3. Follow the notebook instructions to load the model and classify your images.

## Key Features
- **High Accuracy:** The KNN model achieves an accuracy of 86.5% on the test dataset.
- **Ease of Use:** The client notebook (`Client.ipynb`) allows users to directly utilize the pre-trained model.
- **Flexibility:** You can use the `knn-image-classification.ipynb` notebook to train the model on your own dataset.

## Here is the Result:
![Sample 1](https://github.com/user-attachments/assets/92972445-a6e7-4644-8f02-a6a348d222cf)
![Sample 2](https://github.com/user-attachments/assets/502132f0-32e7-4770-9875-faeec9475caa)
![Sample 3](https://github.com/user-attachments/assets/3a1b8265-a802-4cc0-9d09-b0449b900240)



## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Inspired by the simplicity and effectiveness of KNN for image classification.
- Built with the help of open-source Python libraries.

## Feedback and Contributions
If you have suggestions or would like to contribute, feel free to create an issue or submit a pull request. Feedback is always welcome!

[Check out My Kaggle](https://www.kaggle.com/alisalimkhani)

---
<p align="center">
  Made with ❤️ by <a href="https://github.com/AliSalimkhani">Ali Salimkhani</a>
</p>
