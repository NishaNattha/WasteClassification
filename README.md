# Waste Classification Using SVM, ANN, and CNN
This project explores waste classification into five categories, utilizing Support Vector Machines (SVM), Artificial Neural Networks (ANN), and Convolutional Neural Networks (CNN). It represents my first attempt at a computer vision project, including dataset collection, dataset preparation, model development, and evaluation.
Although the project faced significant challenges, it served as a crucial learning experience, helping me understand the nuances of image processing, machine learning, and dataset preparation.


### Objective

To classify waste into five categories (plastic, paper, glass, metal, waste) based on image data.

#### Dataset
  Image 5 classes (150 images per class)

#### Data Collection:
  Created a custom dataset by collecting images using PyCrawler and downloading publicly available images. The dataset includes diverse objects such as plastic straws, paper straws, plastic containers, and other materials.

*Challenges*:
  - Small Dataset: The limited size of the dataset reduced the model's ability and quick overfitting.
  - Similar Objects Across Classes: Items like plastic and paper straws appeared visually similar, causing misclassifications.
  - Multiple Objects Per Class: Variations within a single class (e.g., plastic containers, plastic straws, and plastic glasses) added complexity.
  - Experience Gap: Lack of prior experience with computer vision techniques led to a steep learning curve in preprocessing and feature extraction.

#### Models Developed
  - Support Vector Machine (SVM):
    Used for baseline performance. Limited success due to insufficient feature extraction from raw image data.
  - Artificial Neural Network (ANN):
    Built a basic ANN to classify flattened image data. Faced overfitting due to the small dataset.
  - Convolutional Neural Network (CNN):
    Implemented a simple CNN architecture to extract spatial features. Achieved better performance compared to SVM and ANN, with an accuracy of around **60%**.

#### Attempt to evaluation
  Hyperparameter Tuning, Added other's dataset, Using Regularization, Using pre-trained ResNet (All not working, not in notebook)

#### Technologies Used
- Programming Languages: Python
- Frameworks: TensorFlow, Keras
- Libraries: NumPy, Pandas, Matplotlib, scikit-learn

#### Future Improvements
- Expand Dataset
- Object Segmentation
- Focus on misclassified samples

***Due to file size limitations, the dataset is not included in this repository. If you're interested in accessing the dataset, feel free to contact me directly for more details.***
