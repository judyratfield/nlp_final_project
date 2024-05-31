# COMP8420 2024S1 Major Project

# Integrating Audio Analysis with NLP for Enhanced Sentiment and Intent Recognition in Customer Interactions

__Alfafara, Rodulfo II Dela Paz__ ()
__Guzman, Jelene Delos Santos__ (47499095)

## Statement of the Problem

Current NLP semantic analysis solutions have significant limitations, primarily because they focus exclusively on analyzing text context. This narrow approach often leads to miscategorization of intents, as it disregards intonations and other non-verbal audio cues. For instance, a statement like "Can you help me please?" might be labeled as neutral by most NLP contact center solutions, but if the speaker is shouting, the sentiment should be categorized as angry rather than neutral.

Similarly, phrases such as "Very good! Job well done!" may seem positive when analyzed purely as text. However, if delivered with a high, sarcastic intonation, the sentiment should be recognized as negative. Additionally, non-verbal nuances like sighs, groans, and background noises can indicate negative sentiment, which are often overlooked by existing solutions.

Our project addresses this issue by integrating an analysis of waveforms, frequencies, and other audio characteristics into semantic analysis, providing a more accurate understanding of the speaker's intent and sentiment.

## This repository consists of the following notebooks:

1) Text Semantic Analysis - processes text and performs NLP semantic analysis techniques. This notebook should output semantic analysis ratings for the dataset. 

2) Audio Signals Analysis - processes audio signals that accompanied the text of the dataset and performs audio signals analysis techniques. This notebook should output audio signals readings for the dataset. 

3) Pre-processing_Merge - merges the outputs of 1 & 2 above into one dataframe then we label the data. Or we ask LLM to help us label? 

4) 1D Convolutional Neural Network Model Training - takes the output of #3 as inputs and performs 1D Convolutional Neural Network Model training. Outputs the best model. 

5) Classify - use the best model from #4 for inference & evaluation on test data.