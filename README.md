# BM16_LLMs
Large Language Models (LLMs) in Financial Application

**OVERVIEW**

The repository contains the code and resources necessary to reproduce the research conducted on the application of Large Language Models (LLMs) for financial forecasting using textual data. The project investigates the efficacy of various LLMs, both pre-trained and fine-tuned, in predicting market trends and improving portfolio management strategies.

**REPOSITORY STRUCTURE**
1. **BM16_LLM_Finance_WRDS_Tuned.ipynb**: Notebook for fine-tuning LLMs on financial news data and assessing their predictive capabilities.

2. **BM16_LLM_WRDS_Finance_RollingWindow.ipynb**: Notebook for processing financial news data, extracting features using untuned LLMs, and evaluating their performance.


**TOOLS and PACKAGES**

Ensure the following packages with same versions are installed in your environment. Use ‘requirements.txt’ file to install all packages.

**General Libraries**
1.	Python – 3.10.12
2.	numpy – 1.26.4
3.	pandas – 2.1.4
4.	matplotlib -3.7.1
5.	seaborn – 0.13.1
6.	scikit-learn – 1.3.2
7.	plotly – 5.15.0
8.	wrds (for accessing WRDS)

**NLP and Deep Learning Libraries:**
1.	transformers – 4.24.4
2.	torch – 2.4.0+cu121
3.	nltk – 3.8.1
4.	datasets – 2.21.0
5.	tensorflow – 2.17.0

NOTES

1. Data Access: Access to WRDS. Make sure you have the credentials.
2. Computational Resources: Fine-tuning requires significant computational power. It is highly recommended to use a GPU-enabled environment.
3. Logging and Checkpoints: All logs and model checkpoints are stored in the ‘{user_specified_path}/BM16_LLMs/Finance/results/’ and ‘{user_specified_path}/BM16_LLMs/Finance/models/fine_tuned/’ directories.
4. Data for Market Analysis is already present in the repo in the ‘BM16_LLMs/finance/data’ directory as the data extraction process was manual.
5. Due to size restrictions, data for transaction cannot be uploaded in Git. You can download the data from Drive and place it in the data directory. 
**link:** https://drive.google.com/drive/folders/116uYNtZZoTl29x4cIMU5czmt92m4brDR?usp=drive_link

