In this folder, I will be testing Cohere's open source multi lingual language model for translating an english text.

The text that I will be using to test the model's translation capabilites is the following:

Sample sentence = '''Vegetables are an essential component of a healthy diet, providing a rich source of vitamins,
minerals, fiber, and antioxidants. They come in a wide variety of types and colors, each offering unique
health benefits. Leafy greens like spinach and kale are packed with iron and calcium, while root vegetables
like carrots and sweet potatoes are high in beta-carotene and vitamin A. Cruciferous vegetables such as
broccoli and Brussels sprouts contain compounds that may have cancer-preventive properties.
Incorporating a diverse array of vegetables into daily meals can support overall health,
boost immune function, and reduce the risk of chronic diseases.'''

This family of models is called aya-23 and from this family I will be using 4 bit quantised version of the aya-23 8B to test the translation capabilities of the model.
This family of models support the following 23 languages, and I will be translating the english text into all 23 languages.
Languages supported by the model:
Arabic, Chinese (simplified), Chinese (traditional), Czech, Dutch, French, German, Greek, Hebrew, Hindi, Indonesian, 
Italian, Japanese, Korean, Persian, Polish, Portuguese, Romanian, Russian, Spanish, Turkish, Ukrainian, Vietnamese


More details about the model can be found in the following link: https://huggingface.co/CohereForAI/aya-23-8B


