# Azure Space: Diversity in STEM

This repository contains the code used in the "Azure Space: Diversity in STEM" course. The aim of this course is to promote diversity and inclusion in the field of space exploration. We draw inspiration from Marvel Studios' series "Guardians of the Galaxy Vol. 3", where individuals from different backgrounds, species, and planets, each with their unique set of skills and perspectives, are capable of overcoming seemingly insurmountable challenges and save the galaxy. Just like the Guardians, we believe that diversity of thought and experience can help us achieve our goals in space exploration, on Earth, the galaxy, and beyond.

## About the Code

The code in this repository is used to manipulate weather data related to rocket launches. We use the Scikit-learn machine learning package and a decision tree model (DecisionTreeClassifier) to predict when it is viable to launch a rocket based on weather conditions.

## Environment Setup

To run the code in this repository, you will need to have Poetry installed, a dependency manager for Python.

1. Install Poetry if you haven't already. You can find installation instructions [here](https://python-poetry.org/docs/#installation).

2. Clone the repository and install the dependencies with the following command:

    ```
    poetry install
    ```

3. Access the virtual environment using the following command:

    ```
    poetry shell
    ```

4. You can now run the code in the `rocket_launch.ipynb` file.

Additionally, if you are working on Ubuntu, you will need to install Graphviz, which is used to visualize decision trees. You can do this with the following command:

    ```
    sudo apt install graphviz
    ```

## Contributing

[Azure Space: Diversity in STEM Challenge](https://learn.microsoft.com/en-us/training/challenges?id=0930ea64-19d4-4524-8e96-3523d3b5108c)