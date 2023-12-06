# house-price-visualization
Melbourne House Price Visualization.

This is a machine learning project that predicts house prices in Melbourne, Australia. The project uses historical data on house prices in Melbourne to train a model that can predict the price of a new house given a set of features such as number of rooms, location, and size.

Project Structure
data: contains the training and testing data files
models: contains the trained models
notebooks: contains the Jupyter notebooks used for data exploration, model training, and evaluation
predictions: contains the output predictions from the trained models
src: contains the source code for the project

Getting Started
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your_username/melbourne-house-prices.git
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Navigate to the notebooks directory and run the Jupyter notebooks to explore the data and train the models.

Once you have trained a model, run the predict.py script to generate predictions on the test data:

bash
Copy code
python predict.py
The predictions will be saved to the predictions directory.

Screenshot
Map of Melbourne showing house prices

This screenshot shows a map of Melbourne with the predicted house prices for different regions. The darker the color, the higher the predicted price.
![image](https://user-images.githubusercontent.com/83301253/229288373-ea7833a1-5818-46f1-904d-3e3ec7056108.png)
