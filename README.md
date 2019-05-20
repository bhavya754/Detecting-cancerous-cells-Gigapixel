### Members:

Vatsala Swaroop (vs2671), Bhavya Shahi (bs3118), Ketakee Nimavat (kkn2112)

**Github link**: https://github.com/bhavya754/applied-dl/

**Youtube link**: 

The submission contains 7 Jupyter notebooks:

For single scale run in order -

1. 001_gen_data_level4_single.ipynb:	Contains code to generate patches for magnification level 4. This data is then saved for future use in our experiments

2. 002_gen_data_level5_single.ipynb:	Contains code to generate patches for magnification level 5, along with data augmentation code. The tumor patches are augmented and the data is saved for future use

3. 003_experiments_level4_single.ipynb:	Experiments are conducted on level 4 to compare between CNNs and Transfer learning.
4. 004_experiments_level5_single.ipynb:	Experiments are conducted on level 4 to compare between CNNs and Transfer learning, along with a comparison between original and augmented data for training



For multi scale - run in order -


5. 005_gen_data_multiple_levels.ipynb:	Generates data for multi scale architecture and saves the data in files for future use

6. 006_experiments_multiple_levels.ipynb : Models are created in this and fitted to the data set. This notebook saves the models for future use in evaluation (Note: for some reson, the epoch runs were not saving in the notebook, but we can see the training and testing curves plotted)

7. 007_multiple_levels_test_evalution.ipynb : Loads our two main models and evaluates it on 3 test images. This notebook also contains summary of experiments done, analysis, results, future work, utility and notes on metric design


We uploaded all our files on GCP and we assume that the slides are in the same folder in which the notebook is being run. We ran our models on a 16 CPU, 1 GPU VM instance.

We had to split out project into several notebooks since memory overflow, and GPU utilisation was an issue, causing several failures. We decided to isolate the functionality to enhance readability and re-usability


Project Summary.pdf contains a summary of the project.



