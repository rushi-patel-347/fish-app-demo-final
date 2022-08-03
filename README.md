# Build a ML model for the Fish market dataset
Task : Classification problem to determine the fish species</br></br>
Database : https://www.kaggle.com/datasets/aungpyaeap/fish-market</br>
</br>
Content : This dataset is a record of 7 common different fish species in fish market sales. With this dataset, a predictive model classify the fish species based on height, weight, width and length1, length2 and length3.
</br>

Features:

Species (str): The type of fish</br>
Weight (int): The recorded Weight of the fish in grams (g)</br>
Length1 (int): Vertical length in centimeters </br>
Length2 (int): Diagonal length in centimeters </br>
Length3 (int): Cross length in centimeters </br>
Height (int): Height in centimeters </br>
Width (int): Diagonal width in centimeters</br>

Heroku access link : https://fishmarket-test.herokuapp.com/predict</br>

Installation Required:</br>
python==3.8
Flask==2.1.2</br>
gunicorn==20.1.0</br>
itsdangerous==2.1.2</br>
Jinja2==3.0.3</br>
MarkupSafe==2.0.1</br>
Werkzeug==2.0.2</br>
numpy>= 1.18.5</br>
scipy>=1.8.0</br>
scikit-learn>=0.24.2</br>
matplotlib>=3.3.4</br>
pandas>=1.4.2</br>
Cython== 0.29.30</br>
</br>


Deployment Steps:</br></br>
1. Create a model based on the dataset and integrate model prediction as Flask API </br>
2. Commit all the changes on GitHub </br>
3. Create a Heroku app and link with the Github repository </br>
4. Deploy the Heroku application </br>
