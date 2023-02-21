# Natural Language Processing with Disaster Tweets

Link of the competition: 

https://www.kaggle.com/competitions/nlp-getting-started


This repository contains code and documentation for the Kaggle competition, Natural Language Processing with Disaster Tweets. The goal of this competition is to build a machine learning model that predicts which Tweets are about real disasters and which ones aren't. The repository contains a Jupyter notebook with the code for the model, as well as additional documentation and resources.

## Getting Started

To get started with this project, you will need to do the following:

1. Clone the repository to your local machine.
2. Install the necessary Python libraries. You can find a list of the required libraries in the `requirements.txt` file.
3. Download the data for the competition from Kaggle and place it in the `data` folder.
4. Open the Jupyter notebook and run the code to train and evaluate the model.

## Contents

The repository contains the following files and folders:

- `data/`: This folder should contain the data for the competition. You can download the data from the competition page on Kaggle.
- `notebooks/`: contains a Jupyter Notebook that provides an in-depth analysis of the data used in this project. The notebook walks through the various steps of data cleaning, exploration, and visualization. It also provides insights into the data that helped to guide the feature engineering and modeling phases of the project.
- The `src/` directory contains the Python class that implements the machine learning model used in this project. The class is thoroughly documented and provides methods for training, prediction, and evaluation of the model. To use the class in your own projects, simply import it and create an instance:
- `requirements.txt`: This file lists the Python libraries required for the project.
- `README.md`: This file contains documentation for the project.

The `tests/` directory contains a suite of unit tests that ensure the correctness of the implementation. The tests cover the major methods of the DisasterTweetsClassifier class and test a variety of input and output scenarios. To run the tests, make sure you have the pytest library installed (listed in requirements.txt) and run the following command from the root directory of the project:

## Dependencies

This project requires the following Python libraries:

- pandas
- numpy
- sklearn
- tensorflow
- keras

You can install these libraries using pip:

pip install -r requirements.txt

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
