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
