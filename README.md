# Fake_News_Detection_Model
Using data available from kaggle, we shall conduct appropriate data cleaning, exploratory data analysis and train predictive models to determine whether a news article from our test set is FAKE or REAL. The dataset used for this project was in the form of a .csv file on kaggle. The dataset can be downloaded via the link below:

https://www.kaggle.com/datasets/antonioskokiantonis/newscsv

The files within this repository include:
- *requirements.txt*: This text file contains the dependencies that your virtual environment will need in order to run the python script.
- *detect_fake_news.ipynb*: This python interactive notebook contains the data story behind the whole process which concludes with the best performing model discovered.
- *Fake News Data Dashboard*: This file contains the Power BI dashboard, along with the relevent data, that attempts to visiualise the initial dataset used during this project. This bashboard, when loaded correctly, should look similar to the following:

![Screenshot (59)](https://user-images.githubusercontent.com/116043233/212573897-76c38d55-f65a-4e5d-8abe-ef173e365295.png)

- *GradientBoostingClassifier*: This folder contains various information regarding the Gradient Boosting model used during this project, including the model itself, the parameters the model used in a JSON file, the perfromance metrics of the model on the validation set and the confusion matrix produced in a .png file.

- *Model Metrics Dashboard*: This fiel contains the Power BI dashboard, along with the relevent data, that illustrates the difference in performance of the best performing models of each type.  The a screenshot of the dashboard is shown below.

![Screenshot (61)](https://user-images.githubusercontent.com/116043233/212742618-cf6731f7-a6b0-4539-9739-0bac52d2453f.png)
