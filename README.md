# SMS-Spam-Classification-Hugging-Face-Transformer

Overview
--------
This repository has a jupyter notebook (Notebook.ipynb) containing python code for fine-tuning a BERT (bert-base-uncased) model on an SMS dataset. This is a Sentiment-Analysis task that predicts whether a given SMS is a SPAM or a NOT SPAM. The Hugging Face Ecosystem and Google Colab (GPU accelerated environment) are used for this project.

Results
-------
|Training Loss|	Epoch| Step| Validation Loss|	Accuracy|	Precision| Recall| F1|
|:-|:-|:-|:-|:-|:-|:-|:-|
|0.0828|	1.0|	593|	0.0538|	0.9892|	0.9725|	0.9464|	0.9593|
|0.0269|	2.0|	1186|	0.1792|	0.9677|	0.8244|	0.9643|	0.8889|
|0.0229|	3.0|	1779|	0.0623|	0.9916|	0.9817|	0.9554|	0.9683|
|0.0043|	4.0|	2372|	0.0637|	0.9904|	0.9815|	0.9464|	0.9636|

Usage
-----
- Access the fine-tuned model through the inference widget available at: https://huggingface.co/shre-db/bert-base-uncased-finetuned-smsspam
- Base Model: https://huggingface.co/bert-base-uncased
- Dataset is available at: https://huggingface.co/datasets/sms_spam

Warning!
--------
This model was fine-tuned without using a validation set, which means that the test set was used to monitor the model’s performance during training. This can lead to data snooping bias, which is a form of overfitting that occurs when the model learns from the test data and produces optimistic results that do not generalize well to new data. Therefore, the results of this model may not be reliable or accurate and should be interpreted with caution. The hyperparameters of this model were also not optimized, which means that there may be better settings that can improve the model’s performance. We recommend using a validation set and optimizing the hyperparameters before using this model for any serious task." 
