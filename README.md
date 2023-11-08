## Deploying our Model using Streamlit
Streamlit Web Application which predicts the salary of a software engineers based on the data from stackoverflow

## Dataset
Dataset available at :
[Salary Dataset](https://insights.stackoverflow.com/survey)

### Requirements
You must have Scikit Learn, Matplotlib Pandas and Numpy.

- $ Pip install streamlit

###  App
[Streamlit](https://streamlit.io/) A faster way to build and share data apps

### Running the project
1. Ensure that you are in the project home directory. Run the notebook "Salary-Prediction.ipynb" first

This would create a serialized version of our model and save it as "saved_steps.pkl"

2. Run app.py using below command to start Streamlit API
```
streamlit run app.py
```
By default, streamlit will run on port 8501.

3. Navigate to URL http://192.168.100.184:8501 (or) http://localhost:8501

You should be able to view the homepage.

Select the activity which you want, Explore or Predict 

If everything goes well, you should Visiualize the data from Explore page or Predict the data from Predict page

If you like the project . Give it a star  ⭐ and   ```[FORK]```

