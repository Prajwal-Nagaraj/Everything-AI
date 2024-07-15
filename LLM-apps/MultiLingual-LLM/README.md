# Multilingual Translation Testing with Cohere's Aya-23 Model</span>
## Overview
In this repository, we will test Cohere's open-source multilingual language model, aya-23, to evaluate its translation capabilities. Specifically, we will use the 4-bit quantized version of the aya-23 8B model to translate an English text into 23 supported languages.

## Test Text
The sample sentence used for testing the model's translation capabilities is as follows:
Sample sentence = '''Vegetables are an essential component of a healthy diet, providing a rich source of vitamins,
minerals, fiber, and antioxidants. They come in a wide variety of types and colors, each offering unique
health benefits. Leafy greens like spinach and kale are packed with iron and calcium, while root vegetables
like carrots and sweet potatoes are high in beta-carotene and vitamin A. Cruciferous vegetables such as
broccoli and Brussels sprouts contain compounds that may have cancer-preventive properties.
Incorporating a diverse array of vegetables into daily meals can support overall health,
boost immune function, and reduce the risk of chronic diseases.'''

## Model Details
The model family used for this test is called aya-23. For more details about the model, visit the link here: https://huggingface.co/CohereForAI/aya-23-8B

## Supported Languages
The aya-23 model supports translation into the following 23 languages:

-  Arabic
-  Chinese (simplified)
-  Chinese (traditional)
-  Czech
-  Dutch
-  French
-  German
-  Greek
-  Hebrew
-  Hindi
-  Indonesian
-  Italian
-  Japanese
-  Korean
-  Persian
-  Polish
-  Portuguese
-  Romanian
-  Russian
-  Spanish
-  Turkish
-  Ukrainian
-  Vietnamese

## Testing Procedure
We will translate the provided English text into each of the 23 supported languages using the aya-23 8B model. The results will be documented and analyzed to assess the model's translation quality.

## Repository Structure
translations.txt: Contains the translated texts in 23 languages.   
Multi_Lingual_SLM.ipynb: Contains the notebook used for translation


