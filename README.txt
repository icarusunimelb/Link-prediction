./ comp90051-2020-sem2-proj1
./ data_processing 
./ sampling.ipynb
./ feature_extraction.ipynb
./ training.ipynb

The order to run the program is sampling.ipynb -> feature_extraction.ipynb -> training.ipynb.

comp90051-2020-sem2-proj1 is a folder which will store the source data including train.txt and test-public .txt

data_processing is a folder to store the data generated in the process of sampling, feature extracting and traing. The predict result will also be output to this dir. 

sampling.ipynb is used for data sampling. The positive, negative and test data will be stored in csv file. The community information will be stored in npy file. 

feature_extraction.ipynb will read the sampling and test data from data_processing folder and extract feature. The processed data will be write to training_data.csv and testing_data.csv under the data_processing folder.

training.ipynb will read the training data and test data from data_processing folder and train model. The predict result will be write to submit.csv.