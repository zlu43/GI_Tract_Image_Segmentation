## Files
The directory contains the following files and subdirectories:
- collect_meta_data.ipynb: collect the metadata of the dataset and generate a .csv file for the convenience of loading data
- generate_2.5d_data.ipynb: demonstrate the process of generating 2.5D data
- main.ipynb: the main notebook that defines the models, transformations, and everything else. Configure the hyperparameters and train and evaluate the models here.
- data: dataset is not included due to its size but should generally have this folder structure:
	- scans
		- train
			- case2
				- case2_day1
					- scans
						- slice_0001_266_266_1.50_1.50.png
						...
	- masks
		- train
			- case2
				- case2_day1
					- scans
						- slice_0001_266_266_1.50_1.50.npy
						...
	- train.csv
	- data.csv


## How to Run the Codes
To train a model, open and run main.ipynb and change the configurations as needed and designate the output directories. The process will be visualized at the end.