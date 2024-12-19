# KNN Image Classifier

Welcome to the **KNN Image Classifier** project! This repository demonstrates a simple yet effective implementation of a K-Nearest Neighbors (KNN) model for image classification. With an accuracy of **86.5%**, this project is a great starting point for understanding and utilizing KNN for image-based machine learning tasks.

## File Structure
This project includes:
- `knn-image-classification.ipynb`: Core notebook for training and saving the KNN model.
- `Client.ipynb`: Client notebook for using the pre-trained model.
- `fire_classifier.z`: Serialized KNN model for image classification.
  

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
pip install opencv
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

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Inspired by the simplicity and effectiveness of KNN for image classification.
- Built with the help of open-source Python libraries.

## Feedback and Contributions
If you have suggestions or would like to contribute, feel free to create an issue or submit a pull request. Feedback is always welcome!

<p align="center">
  Made with ❤️ by <a href="https://github.com/AliSalimkhani">Ali Salimkhani</a>
</p>

---
Thank you for exploring the **KNN Image Classifier** project! 🚀

