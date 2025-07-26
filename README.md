# Football_Sim_1
Developed an unsupervised learning pipeline to analyze outfield football players using clustering (K-Means) and dimensionality reduction (PCA). Engineered player performance features, normalized high-dimensional data, and visualized clusters to identify stylistic similarities. Built a prototype similarity search tool to recommend players with comparable profiles based on statistical performance metrics.


## The dataset is from kaggle and there are two versions:
	•	player_data-2024_2025.csv – Full dataset with comprehensive player statistics.
	•	player_data_light-2024_2025.csv – A lighter version with fewer features, ideal for quick prototyping or resource-limited environments.
 	•	player_data-2024_2025(1).csv – Updated dataset until season end.
	
 

By default, the scripts are compatible with all versions. You can easily switch between them by modifying the file path in the preprocessing section of the notebook or script.

#### football.ipynb was meant as a prototype (mostly for EDA)
#### footballnow.ipynb has a Test-Training- Validation split of the dataset and players are searched only on Validation set.
#### footballwhole.ipynb searches the whole dataset for similar players.
