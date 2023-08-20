# SMS-Spam-Classification-Hugging-Face-Transformer

Overview
--------
This repository has a jupyter notebook (Notebook.ipynb) containing python code for fine-tuning a BERT model on an SMS dataset. This is a Sentiment-Analysis task that predicts whether a given SMS is a SPAM or a NOT SPAM. The Hugging Face Ecosystem and Google Colab (GPU accelerated environment) are used for this project.

Results
-------
|Epoch|	Training Loss|	Validation Loss|	Accuracy|	Precision	Recall|	F1|
|:-|:-|:-|:-|:-|:-|
|1	|0.081200|	0.068059|	0.990442|	0.990566|	0.937500|	0.963303|
|2|	0.026900|	0.079880|	0.984468|	0.938053|	0.946429|	0.942222|
|3|	0.013100|	0.068701|	0.989247|	0.972477|	0.946429|	0.959276|
