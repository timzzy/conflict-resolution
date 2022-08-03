# conflict-resolution
Conflict identification and resolution framework

###The package contains the source code of the following two studies: 
- Evaluating the performance of rule-based method on the mined dataset for extracting features from user feedbacks. 
- Simulate the impact of the dataset and annotation guidelines on tyhe model performance when extracting app features from user reviews

---

## Required Installs

To run the scripts in this, following tools, datasets (both downloaded from kaggle and mined) need to be available. First, advisable that it runs on a GPU, as it stops or hangs when the code is ran on a CPU because of the memory and processor requirements of the project:

#1 Install python >= 3.6, and run the command ''' pip install installs.txt''' to install the required python packages for the jypyter notebook environment

#2 Download app reviews in from Kaggle using the link https://www.kaggle.com/code/mmsant/ratings-and-reviews-and-android-app-success/data and label it as data_kaggle and put in the datasets folder

#3 Use the cell labelled "mined play store" extract reviews from google play an save the reviews in file labeled as playstore.csv in the datasets folder

#4 Use the cell labelled "mined app store" extract reviews from apple an save the reviews in file labeled as appstore.csv in the datasets folder

#5 Install the tool **CRFsuite**, please refer to http://www.chokkan.org/software/crfsuite/installs

#6 Import the coreNLP file in the frameworks folder to call the coreNLP framework from thefolder named framework which housed all the downloaded external frameworks used on this project

# Reviews from Kaggle datasets contains reviews from both android and apple's mobile applications
# Reviews from android datasets contains reviews from android applications 
# Reviews from apple datasets contains reviews from both apple applications
# About seventeen python modules specified in the notebooks needs to be installed on the host machine to run the implementation
