# GPA Predictor 
This project is a GPA predictor for students in Bangladesh. It uses a Random Forest Regressor to predict the GPA of students based on their previous academic performance and other features.

# How to Run 
1. Clone the repository 
```text
git clone git@github.com/arif-z04/ML-gpa-predictor.git
```
2. Install the required libraries using:
```
pip install -r requirements.txt
```   

3. Run the training script using `python rf_train.py` to train the model and save it as `rf_model.pkl`
4. Run the Gradio app using `python app.py` to interact with the model and predict GPA based on user input.

--- 

> Note: The dataset used in this project is not included in the repository. You will need to obtain the dataset and place it in the `data` directory before running the training script.

