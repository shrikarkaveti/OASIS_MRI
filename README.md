# OASIS_MRI

## Steps to Run the Model

1. Run Data_Generator.ipynb to generate the download_dataset.sh file and data_gen_csv.csv

2. download Dataset with the download_dataset.sh file

3. Run Extractor.ipynb to Extract the zip and gz files from the downloaded dataset which creates another file extracted_zip folder and Train_Data folder where the later contains the NII files for training

4. The data_gen_csv has mixed data with some MRIs not having NII files to get the final train_y Dataset csv file Run Train_csv_gen.ipynb
