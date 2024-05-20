# Group1
Optimal Multi-Stage Arrhythmia Classification Approach
team members (Samah khaled (24230025)
Omnia Mohamed (24230007)
Batool yousry (24230012))
first read tha data (https://physionet.org/content/ecg-arrhythmia/1.0.0/WFDBRecords/01/#files-panel) 
paper (https://www.nature.com/articles/s41597-020-0386-x)
kaggle link(https://www.kaggle.com/datasets/erarayamorenzomuten/chapmanshaoxing-12lead-ecg-database)
download file imp and ConditionNames_SNOMED-CT
get the hea file which contain the whole information about the patients there are alot of patients which have more than one disease so we get the patients who only have just one diseas it is afile named (information) attached with the reseaech paper which contaion the id and medical name of each id in the diagnosis column we choose the sb and sr as abnormal and normal because they have the maximum number of patients so it will give high accuracy record information(12 led ,sampling frequancy 500 ,numper of samples 5000 ,age ,sex ,id, ......) 5000 sample taken from 12 lead remove some samples of our data to avoid overfitting and store the new data in kaggle/working/dataset.csv get the p_signal of each patient and store it in (data) Convert the lists to numpy arrays convert text to integer (encoding) convert data and labels to array praparing it for the model Convert data into x=data &y= label splitting the data to train 30% and test 70% we have 3 model 1-cnn model in time domain 2- LSTM model in time domain 3- LSTM model in frequency domain Compute the confusion matrix Compute the Specificity Compute theSensitivity Plotting the ROC curve Compute theAUC
