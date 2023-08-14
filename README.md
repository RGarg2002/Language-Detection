# Language Detection using Multinomial Naive Bayes

The Language Detection using Multinomial Naive Bayes project involves training a machine learning model to classify input text samples into their corresponding languages using the Multinomial Naive Bayes algorithm. This README provides an overview of the project, its features, technologies used, and instructions for usage.

## Features

- Train a text classification model using the Multinomial Naive Bayes algorithm.
- Perform language classification on input text samples.
- Utilize the CountVectorizer from scikit-learn to convert text data into numerical features.
- Evaluate the model's accuracy on a test dataset.
- Provide a user interface for users to input text for language classification.

## Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn
- Multinomial Naive Bayes

## Dataset

The project uses a dataset containing text samples and their corresponding languages. The dataset is available [here](https://raw.githubusercontent.com/amankharwal/Website-data/master/dataset.csv). It includes various languages such as English, Spanish, Chinese, and more.

## Installation

1. Clone the repository:
git clone https://github.com/Rgarg2002/Language-Detection.git

2. Navigate to the project directory:
cd Language\ Detection

3. Install the required packages:
pip install -r requirements.txt

## Usage

1. **Data Preparation:** The dataset is automatically fetched from the provided URL. No manual download is necessary.

2. **Training and Testing:** Run the `detect.ipynb` script to train the Multinomial Naive Bayes model, evaluate its accuracy, and predict the language of user input.

3. **Language Prediction:** After running the script, you can enter text when prompted, and the model will predict the language.

## Output

The script will output the predicted language of the entered text based on the trained Multinomial Naive Bayes model.

## Contribution

Contributions are welcome! Feel free to submit pull requests for enhancements or bug fixes. Please adhere to good coding practices and provide clear documentation.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or suggestions, feel free to contact the project maintainers:
- [Royal Garg](https://github.com/Rgarg2002)
