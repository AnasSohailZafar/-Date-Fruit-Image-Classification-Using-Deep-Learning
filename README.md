# -Date-Fruit-Image-Classification-Using-Deep-Learning
This project focuses on building a convolutional neural network (CNN) model to classify date fruit images into different classes. The model is trained using TensorFlow and Keras, and evaluated using test data. The repository also includes code for data preprocessing, evaluation metrics, and visualization of results.

## Dataset

The dataset used in this project is called the "Date Fruit Image Dataset." It is organized into two directories: `train` and `test`. The `train` directory contains subdirectories for each class of date fruit, and each subdirectory contains images of that class. The `test` directory follows the same structure.

Ensure that you have the dataset properly organized in the `train` and `test` directories before running the code. You can modify the `train_dir` and `test_dir` variables in the script to match the paths to your dataset.

## Dependencies

This project requires the following dependencies:

- TensorFlow
- Keras
- Matplotlib
- Scikit-learn
- Numpy
- Seaborn

You can install these dependencies using pip:

pip install tensorflow keras matplotlib scikit-learn numpy seaborn


## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/date-fruit-classification.git

```
2. Navigate to the project directory:

3. Place your dataset in the appropriate directories (`train` and `test`).

4. Open the `date_fruit_classification.ipynb` file and modify the `train_dir` and `test_dir` variables with the correct paths to your dataset.

5. Run the script

The script will train the CNN model on the training set, evaluate its performance on the test set, generate plots of accuracy and loss, and display a classification report and confusion matrix. The bar charts showing the sample counts per class in the training and test data will also be displayed.

Note: Make sure you have the necessary dependencies installed before running the script.

## Results

After running the script, you will see the test accuracy printed. Additionally, the script will generate plots of accuracy and loss, a classification report, a confusion matrix, and bar charts showing the sample counts per class.

## License

The code in this repository is licensed under the [MIT License](LICENSE).

Contact Information
For any questions or suggestions, please feel free to reach out :

Name: Anas Sohail Zafar

Email: anassohailzafar@gmail.com

GitHub: github.com/AnasSohailZafar

Linkedin: www.linkedin.com/in/anas-sohail-zafar123





