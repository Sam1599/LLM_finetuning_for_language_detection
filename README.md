# Transliterated Language Detection using LLM

Finetuning https://huggingface.co/papluca/xlm-roberta-base-language-detection model for detection of other Indian languages apart from Hindi.

Transliteration is the process of converting text from one writing system into another, with a focus on representing the original text's sounds or phonetic values using the alphabet or script of a different language. For instance, the phrase "Aap kaise ho?" translates to "How are you?" in Hindi, but it is written using the English alphabet. Similarly, "Nee epdi iruka?" translates to "How are you?" in Tamil, also rendered in English script. Transliteration facilitates the understanding and interpretation of diverse languages, making communication more accessible and convenient.

The papluca/xlm-roberta-base-language-detection model has been fine-tuned on the Language Identification dataset, which includes text sequences in 20 different languages. This model is capable of identifying Hindi, an Indian language, as well as various other foreign languages.

The goal is to fine-tune this model to detect other transliterated Indian languages such as Tamil, Malayalam, and Urdu. To achieve this, the https://huggingface.co/datasets/ai4bharat/Aksharantar dataset, which includes 20 Indic language-English transliteration pairs, has been utilized.

A subset of the dataset, containing languages like Tamil, Urdu, and Assamese, has been loaded to fine-tune the model and streamline the training process. After training, the model accurately detects the intended languages.

The model can be further fine-tuned on additional Indian languages and trained for more epochs to enhance its accuracy.

Run this notebook: https://colab.research.google.com/drive/1thWZYcNnbcmd2aZz23qUkv2MpVMoqyMm

