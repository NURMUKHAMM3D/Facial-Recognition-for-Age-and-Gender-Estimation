# Facial-Recognition-for-Age-and-Gender-Estimation

Facial Recognition for Age and Gender Estimation

This project involves the development of a facial recognition model to estimate a person's age and gender using the UTKFace dataset. The project includes two models: one for jointly predicting age and gender and the other with separate models for each task. The implementation is done using Python and TensorFlow/Keras.

Project Link

You can find the complete project repository here: Project GitHub Link

Project Structure

notebooks/: Jupyter notebooks for data exploration, preprocessing, and model training.

models/: Saved models for age and gender prediction.

images/: Sample images for testing the models.

requirements.txt: Python dependencies required for the project.

README.md: Instructions for running the code and details about the project.

Setup Instructions

Requirements

Python 3.8 or higher

Required Python packages are listed in requirements.txt.

To install the dependencies, run:

pip install -r requirements.txt

Dataset

The project uses the UTKFace dataset. Ensure the dataset is placed in the data/UTKFace directory.

Running the Code

Clone the repository:

git clone https://github.com/username/facial-recognition-age-gender.git
cd facial-recognition-age-gender

Install the required dependencies:

pip install -r requirements.txt

Run the Jupyter notebooks for training:

jupyter notebook notebooks/age_gender_estimation.ipynb

To use the trained models for inference:

python scripts/predict.py --image_path <path_to_image>

Special Requirements

Ensure you have a GPU-enabled environment to train the models efficiently.

Install Jupyter Notebook if you want to explore the code interactively:

pip install notebook

Results

Model 1: Achieved 93% accuracy for gender classification.

Model 2: Achieved 87.8% accuracy for gender classification and improved MAE for age estimation.

Contributions

Feel free to open issues or contribute to the project by creating pull requests.

License

This project is licensed under the MIT License. See LICENSE for more information.
