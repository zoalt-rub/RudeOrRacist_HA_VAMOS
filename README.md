# RudeOrRacist_HA_VAMOS
This repo contains all necessary code to replicate the finetuning pipeline employed in the term paper *"Rude or Racist? Distinguishing Hate Speech from Offensive Language Using a Fine-Tuned Transformer Model"*

The model is used for classifying a text as Hatespeech, Offensive, or Neither. The model is trained using data from Gab and Twitter that will loaded within the notebook. As this project was coded on Google Colab and requieres its GPU, opening the Notebook there is recommended. Google Drive access required to save the model.

The data used comes from the HateXplain Dataset (https://huggingface.co/datasets/Hate-speech-CNERG/hatexplain), availabe under the MIT license. 

# Evaluation Results

| Metric     | Validation Set      | Test Set     |
| ------------- | ------------- | -------- |
| Precision          | 0.68        | 0.67 |
| Recall      | 0.69    | 0.68 |
| F1 score        | 0.68         | 0.67  |


# Abstract
Language, especially online, is often crude and insulting. Yet, such statements do not always carry hateful intent. To be effective, automated hate speech detection must be able to recognize this intent and differentiate between hate speech and offensive language. As traditional NLP methods struggle with this distinction, this study investigates whether a finetuned DistilBERT model can differentiate hate speech from offensive language better. The model trained detects hate speech (F1 0.74) and non-offensive speech (F1 0.72) decently, but struggles with the identification of offensive language (F1 0.52), resulting in an overall F1 score of 0.67 on the test set. The loss curves suggest that the model underfitted. I find that the finetune approach to hate speech detection is effective, but has limitations concerning resource use that cause detection issues with more implicit forms of derogation.
