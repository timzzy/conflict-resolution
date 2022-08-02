# conflict-resolution
Conflict identification and resolution framework

###The package contains the source code of the following two studies: 
- Evaluating the performance of rule-based method on the mined dataset for extracting features from user feedbacks. 
- Simulate the impact of the dataset and annotation guidelines on tyhe model performance when extracting app features from user reviews

---

## Required Installs

To run the scripts in this, following tools, datasets (both downloaded from kaggle and mined) need to be available. First, advisable that it runs on a GPU, as it 
swtops or hands when the code is ran on a CPU because of the complexity of the project:

#1. Install python >= 3.6, and run the command ''' pip install requirements.txt''' to install the necessary python packages.u
#2. Install the tool **CRFsuite**, please refer to http://www.chokkan.org/software/crfsuite/
#3. Download annotated app reviews in German called **SANGER** from http://www.romanklinger.de/scare/ and put them in the folder Proprocessing_Scrpts/SANGER_ANNOTATED_REVIEW DATA/. 
#4. Download annotated app reviews in English called **GUZMAN** from https://www.dropbox.com/s/xu0w0tcuq6xgezc/user_feedback_public.sql?dl=0 and put them in the folder Proprocessing_Scrpts/GUZMAN_ANNOTATED_REVIEW DATA/
#5. Download datasets (**LAPTOPS** and **RESTAURANT**) from SemEval-2014 Task 4: http://alt.qcri.org/semeval2014/task4/index.php?id=data-and-tools and put in the evaluation folder.
#6. Download SENNA Embeddings available at http://ronan.collobert.com/senna/ and put in the embeddings folder.
#7. Download Wikipedia Embeddings for German language available at http://ronan.collobert.com/senna/ and put in the embeddings folder.
---
requirements.txt
