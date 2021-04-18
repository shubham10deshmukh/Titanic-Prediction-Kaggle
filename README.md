# Titanic-Prediction-Kaggle
This a machine learning application to a problem hosted in Kaggle.

Link : https://www.kaggle.com/c/titanic/overview

READ ME
Please read this file till the end.
The Zip file contains the following:
1.	The Assignment Report in pdf format.
2.	Python notebook (code file) of the project Titanic_Python_x2020gfv.ipynb
3.	Two Datasets in .CSV format.
4.	The Read Me file.
The Assignment is built on Python 3 using Anaconda IDE on a Jupyter notebook, however the python notebook file can be opened and run in any Python supported environment. However, Jupyter is recommended.
The dataset file "Train.CSV" and "Test.CSV" are the default version of the datasets available in the Kaggle Competition page. Both the files are included in the zip folder.
Two URL variables are mentioned in the start of the code, in which the path of the CSV files are mentioned. The relative paths are already set for both the files.
If you are on Kaggle’s kernel you can use
•	Train.csv: “/kaggle/input/titanic/train.csv”
•	Test.csv : “/kaggle/input/titanic/test.csv”

New path might need to be set in any other computer/desktop for a local file and code to run and execute. 
Technologies/Dependencies used in the project: 
•	Programming Language – Python
•	Libraries: Pandas, Numpy, Sklearn
•	Anaconda IDE
•	Jupyter Notebook for python 3 and supported web browser.
•	Microsoft Excel for viewing CSV files.

Technical Details and Method Details

Please run the main driver code to run the entire program.
	
Please run the above section first this calls every method of the code.
Methods

1.	importData( trainDataURL , testDataURL )
Parameters (2): URL of train.csv and test.csv in string format.
Return (1): Merged Data in DataFrame format 

2.	processData ( mergedDataFrame )
Parameters (1): Merged Dataframe.
Return (1): Processed Data in DataFrame format 

3.	divideData ( mergedDataFrame )
Parameters (1): Merged Dataframe.
Return (3): Three dataframes ( X_train, X_test, Y_train) in DataFrame format 

4.	applyModelRF ( X_train,Y_train,X_test)
Parameters (3): Three Training and Testing Dataframe.
Return (1): Predicted in DataFrame format 

5.	exportResultData (mergedDataframe ,Y_predicted, file)
Parameters (3): Imported Dataframe, Predicted Dataframe and FileName(string)
Exports (1): submission.csv file is exported

