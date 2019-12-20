# House Prices Coco-Tib README

A Kaggle House Prices project

## Getting Started

This project by Coco & Tib includes data exploration and machine learning modeling on the House Prices Kaggle competition. The first file coded with R explores the data and the second file coded with Python applies modeling on the data to make predictions. This workflow is able to create predictions and to submit them directly to the Kaggle competition. Simply execute the notebook cells and go with the flow.

## Installing

This project includes a Docker image that can get you started quickly.

- Clone this repository using Git clone in a bash in the desired directory :

        git clone https://github.com/Simplon-IA-Bdx-1/house-prices-coco-tib.git

    The datasets are included.

Using Docker to run the project :

- Install Docker Desktop.

- Create a auth.env file in the "docker" directory (you can use Notepad) and paste the following lines in it:

        BIGML_USERNAME=XXX
        BIGML_API_KEY=XXX
        KAGGLE_USERNAME=XXX
        KAGGLE_KEY=XXX

- Replace the "XXX" with your usernames and api keys.
- Open a bash in the Docker directory.
- For the first launch, execute the following command in your bash:

        docker-compose up --build

- Open the notebook in any navigator and open the following adress:

        http://localhost:8888/

- If asked for a Jupyter token, copy and paste it from your bash.
- Browse the files from the Jupyter Notebook.
- Once you are finished, execute the following command in your bash:
    
        docker-compose down

- Or simply push the Ctrl+c shortcut in your bash.
- If you want to launch the project again, you don't need to execute the Docker "--build" option again, use the quicker:

        docker-compose up


Alternatively, you can install the prerequired libraries and launch the files with a notebook app such as Jupyter. The list of required libraries is available below.

## How to use

Explore the project:
- First, open HousePricesProjectR.ipynb to look into the data exploration.
- Second, open HousePricesProject.ipynb to apply the machine learning modelling and make predictions.

## Prerequisites

- Git
- Docker Desktop
- (or a Notebook environment)

Python 3.6

- BigML
- numpy
- pandas
- matplotlib
- sklearn.linear_model, LinearRegression
- sklearn.ensemble, IsolationForest
- kaggle

R

- dplyr
- ggplot2
- FactoMineR
- factoextra
- coefplot

## Authors 

Corantin OGIER, Thibaud GROSJEAN

## License

Yolo
