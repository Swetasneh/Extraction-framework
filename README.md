# Auto-Extraction-Framework-for-CEP-rules-using-2-layer-LSTM-attention-mechanism-


**Steps to Run the Code:**

1. Upload the main.ipynb file, rules, rules extraction, dataset, and image files to a drive.
2. Install Apache Flink.
3. Import all necessary Python libraries and frameworks.
4. Import PyFlink for generating data streams.
5. Execute the code for Decision Tree and Random Tree rule extraction algorithms.

**Project Implementation Details:**

- Apache Flink is installed to generate data streams from the provided Delhi Climate unlabeled dataset.
- The goal is to predict rain using parameters such as mean temperature and mean humidity.
- All required Python libraries and frameworks are installed.
- Data is read from the dataset using Pandas.
- Preprocessing involves dropping rows with NaN values.
- LSTM labels the data with binary values indicating rain occurrence.
- PyFlink generates data streams based on the labeled dataset.
- Mean encoding is applied to convert integer values of temperature and humidity to floating values for realism.
- The model is trained using Decision Tree Classifier, and predictions are made on the testing data.
- Rules are extracted from the generated decision tree model.
