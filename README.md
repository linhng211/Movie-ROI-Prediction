DESCRIPTION:

This project focuses on analyzing movie data to predict the return on investment (ROI) and provide interactive visualizations of the findings. The goal is to mine useful features from the data using various NLP techniques and apply machine learning models to predict ROI. Additionally, interactive visualizations are created to communicate the findings effectively. The project includes Jupyter Notebooks for feature extraction, model training, and evaluation, with visualization being done in PowerBI.

INSTALLATION:

To set up and run the project, follow these steps:
	1.	Download the project folder from the provided source.
	2.	Extract the folder contents to a desired location on your machine.
	3.	Navigate to the project directory in your terminal or file explorer.
	4.	(Optional but recommended) Create a virtual environment:

python -m venv venv


	5.	Activate the virtual environment:
	•	On Windows:

venv\Scripts\activate


	•	On macOS/Linux:

source venv/bin/activate


	6.	Install the required dependencies:

pip install -r requirements.txt



EXECUTION:

To run the project and generate the necessary outputs using Jupyter Notebooks:

	1.	Install Jupyter (if not already installed):

pip install notebook


	2.	Launch Jupyter Notebook:

jupyter notebook


	3.	Open the following notebook files:

	• data_manipulation.ipynb – for loading and preparing the base data for the project.
	• NLP_feature_mining.ipynb – for extracting features from the text data.
    	• success_classification.ipynb – for classifying the sucess of movies based on thier reviews.
	• revenue_prediction.ipynb – for predicting revenue, which is then used to calculate ROI, for the final goal of the project: ROI prediction.

	4.	Execute the cells step-by-step for each of the files in the described order to process the data, train the model, and generate the necessary outputs.

	5.	The output files (e.g., predictions, feature importance) will be saved in the folder and can be used for further analysis and visualization.

PowerBI Integration:

The output files from the model and feature extraction processes will be uploaded into the PowerBI file to feed the interactive visualizations. These files are stored in the project folder for easy access.
