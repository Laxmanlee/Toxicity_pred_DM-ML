# Toxicity_pred_DM-ML

I have been working on the code using Google colab for the whole competitiojn.
So, I had to use the "pip install packagename" command to install RDkit, xgboost and catboost packages to import RDkit descriptors, Gradientboostclassifier and Catboostclassifier to predict the toxicity of the chemicals in the data provided.

The following segment carrying the code related to RDkit descriptors as below :
from rdkit.Chem import Descriptors

for name,function in Descriptors.descList:
  print(name, function)
  
the above command gives us the 208 descriptors being able to generate of RDkit package.

Once the above commands are run, then you can just upload the files train_II.csv and test_II.csv before you initiate the run of the code to deliver hte prediction file "predictions.csv"


The next segment carries the code of internal evaluation using K-fold cross-evaluation which can be run at any time to check your score internally.


All you need is either a online notebook editor like Google colab, Jupyter, Kaggle kernel or any online kernel notebooks which is able to execute python code. Else, you can download the trials_toxic.ipynb file as provided and then run it through applications like VisualStudioCode, Pycharm or any coding applications supporting python code execution.
