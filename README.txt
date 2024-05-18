This repository consists of the following notebooks:

1) Text Semantic Analysis - processes text and performs NLP semantic analysis techniques. This notebook should output semantic analysis ratings for the dataset. 

2) Audio Signals Analysis - processes audio signals that accompanied the text of the dataset and performs audio signals analysis techniques. This notebook should output audio signals readings for the dataset. 

3) Pre-processing_Merge - merges the outputs of 1 & 2 above into one dataframe then we label the data. Or we ask LLM to help us label? 

4) GNN Model Training - takes the output of #3 as inputs and performs GNN model training. Outputs the best model. 

5) Classify - use the best model from #4 for inference & evaluation on test data.