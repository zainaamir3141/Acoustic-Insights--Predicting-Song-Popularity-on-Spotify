The goal of this project is to review if the acoustic features can predict the popularity of a song. It is based on 2017 Spotify data with enhanced feature data per song from Spotify API using Spotipy library.

All scripts are Jupiter notebook files (.ipynb)

Included in the zip file you can find 3 csv files and 3 .ipynb:

	CSV Files:
		spotify_data.csv #original Spotify dataset from Kaggle
		all.csv #country names + codes

	.ipynb Files:

		1_AML_Process_Basic_Data 
			Input: all.csv, spotify_data.csv
			Main Output: merged_original_and_audiofeatures.csv 
  
		2_AML_EDA 
			Input : merged_original_and_audiofeatures.csv
			main output: EDA Plots

		3_AML_MODELS_FINAL 
			Input : merged_original_and_audiofeatures.csv, 
			Main Output: Plots , scores and performance metrics from models
			Other Outputs: Other csv files with intermediate results

Instructions to run the Scripts:


1. Place all .csv and .ipynb files within the same folder (let's call it origin folder, ex ~/HOME)
2. Make sure you have the following python version and libraries installed in your current env or create an env with the following specs (read requirements.txt):

Python Version:
  Python 3.9.12

Libraries Installed:
	numpy==1.21.15
	pandas==1.4.2
	matplotlib==3.5.1
	matplotlib-base==3.5.1
	matplotlib-inline==0.1.2
	scikit-learn==1.0.2
	scipy==1.7.3
	seaborn==0.11.2
	plotly==1.0.0
	spotipy==2.20.0

3. You can run all files in order (1,2,3).

In order to run scripts (within correct env*) open Anaconda -> Kernel -> Restart and Run All.

4. View the results inside of the 3_AML_Models_Final notebook OR open plots / intermediate csv files created after running the notebook inside the origin folder.







