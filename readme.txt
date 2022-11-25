Youtube Link: 

		https://youtu.be/eB3dzgk4LRc

DataSet:

		https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

	
	DescrIption: 

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.


Code execution steps: 

Execute cell by cell from chest_x_ray_code.ipynb. Put Jupyter Notebook on your device exactly as it is in a github folder with a dataset.

	Github Link: 

		https://github.com/PakAnna/Chest_x_ray_MA_Project

Also you can use load_model function from keras.models to load 'chestxray.h5' model and test it, without training.