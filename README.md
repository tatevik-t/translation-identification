# Translation identification models

Translation identification task is to determine whether 2 sentences in different languages are translated plagiarism or not. Here are presented transformer-based model XLM-RoBERTa, which is fine tuned for this task.


## The models

[XLM-RoBERTa-base](https://huggingface.co/jplu/tf-xlm-roberta-base) was trained on the generated 14 different training sets (one for each of the following languages: [English, Dutch, Swedish, Spanish, Portuguese, French, Russia, Serbian, Czech, Armenian], 3 for subfamilies: [Germanic, Romanian, Slavonic], and 1 for all 10 languages). Each of these training sets consists of sentences written in one of the presented languages paired with sentences written in English. Examples were generated using sentences from Wikipedia.

Trained XLM-RoBERTa models are in the [onnx](https://onnx.ai/) format are in the [google drive folder](https://drive.google.com/drive/folders/14G4Obufi3qg4NvscFB2AYAqR6ChgjPLG?usp=sharing).


## The code
Code to run model is presented in [run_models.ipynb]() notebook.
