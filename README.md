# mlhc2024 Final Project
### Demographic Bias of Medical Condition in GPT-4 Across Different Languages
group member: Yuxin Xiao, Grace Guo, Nancy Zha, Kailin Xu

### Prerequisites

Before running the notebook, ensure you have the following:
Python 3.8 or later
The following Python packages installed:
numpy
pandas
matplotlib
seaborn
scikit-learn
You can install the necessary Python packages using pip:
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

### Visualization
File: viz.ipynb
Data: 
* data/Chinese.csv: GPT-4 result from Chinese prompts
* data/English.csv: GPT-4 result from English prompts
* data/True.csv: processed data of true disease prevalence   
* data/final_true_dist.csv: raw data of true disease prevalence in the United States from Zack et al. 

Structure: 
* Data Loading: load the disease prevalence data from CSV files.
* Data Preprocessing: perform any cleaning or transformation of the data.
Data Analysis: execute the statistical analysis comparing actual and predicted disease prevalences.
Visualization: generate plots and visualizations of the results.


### References
Travis Zack, Eric Lehman, Mirac Suzgun, Jorge A Rodriguez, Leo Anthony Celi, Judy Gichoya,
Dan Jurafsky, Peter Szolovits, David W Bates, Raja-Elie E Abdulnour, et al. Assessing the
potential of gpt-4 to perpetuate racial and gender biases in health care: a model evaluation study.
The Lancet Digital Health, 6(1):e12–e22, 2024.

