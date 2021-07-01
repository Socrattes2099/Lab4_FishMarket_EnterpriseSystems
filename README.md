# Fish Classifier based on dimensions

## Description
Machine learning model that use Logistic Regression to predict the specie of a fish given its physical dimensions:
- Weight (g)
- Vertical Length (cm)
- Diagonal Length (cm)
- Cross Length (cm)
- Height (cm)
- Diagonal Width (cm)

The dataset 'Fish.csv' used for training of the model is located in the root directory.


## Installation
1. Install dependencies by executing 'pip install -r requirements.txt' in the console

## Usage
1. Open the Jupyter notebook file 'Model_fish_market.ipynb' to test the Logistic Classifier
2. Model is saved as 'model.pkl'
3. Execute file 'FlaskApp.py' to open Flash webserver
4. Open the URL http://127.0.0.1:5000/ in a web browser
5. Type in the dimensions of the fish
6. Click the button 'Predict Fish'
7. See prediction in next page.

## License
Licensed under the MIT License

## Authors
Bayron Guevara

## Credits
This dataset was taken from [Kaggle](https://www.kaggle.com/aungpyaeap/fish-market)

## How to contribute
You can submit a pull request containing a model that can lead better accuracy
