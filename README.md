# Topsis_forPretrainedModels
Overview

Our aim to compare the performance of various text summarization models, assisting users in selecting the most suitable model based on their specific requirements. The evaluation focuses on essential metrics such as Rouge scores, length of the summary, and training time.

Metrics Considered:
Rouge Scores: Assess the quality of generated summaries.
Length of Summary: Provides insights into the summary length.
Training Time: Evaluates efficiency and resource requirements.

Methodology - TOPSIS:
The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method is employed for a comprehensive ranking. It considers both similarity to the ideal solution and dissimilarity to the negative ideal solution.


Models Evaluated:
Real-world pretrained models, including BERTSumAbs, GPT-2, DistilBERT, BARTLarge, CTRL, BERTExtractive, BERTSumExt, T5	
Pegasus are included in the comparison. These models are widely used in text summarization tasks.

Files:

data.csv: CSV file containing evaluation metrics for each model.

result.csv: CSV file with ranked results in tabular format.

result.csv: CSV file with data used for creating a bar chart.

barchart.png: Bar chart visualizing the model comparison.

Analysis:

Model Performance: BARTLarge outperforms other models in terms of Rouge scores, securing the top rank. BERTSumExt and GPT-2 follow closely, showcasing competitive performance. 
