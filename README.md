# Corpus-TLoU-Dialogues
Corpus (baed on The Last of Us video game) and GPT LLM to detect polarity and emotions in video game dialogues

The Excel of this repository corresponds to a corpus of texts extracted from the video game "The Last of Us" (TLoU), incorporating some dialogues from the second part of the video game also to enrich the dataset. This dataset has 2,077 samples (TLoU dialogues) and consists of six variables: Chapter, Character, Gender, Text, Polarity and Emotions which are described as follows:

1. Chapter: TLoU chapter when the message is said.
2. Character: The message issuer.
3. Gender: Character gender.
4. Text: a variable that represents the message extracted from the game dialogue (raw). This variable will require additional processing to analyse it.
5. Polarity: One of the target variables that can take three values depending on the polarity of the message, namely Positive (P), Negative (N), and Neutral (NEU).
6. Emotion: One of the target variables that can take six values depending on the emotion of the message: Anger, Empathy (Empahty/Trust), Fear, Happy, Neutral, Sad, Surprised.

The files in the LLM folder serve to 1) preprocess the data in the corpus, and 2) execute the OpenAI Platform models through Jupyter-notebooks to train, validate and test polarity and emotions.

## Contact

This development belongs to the research collaboration about Natural Languange Processing through Large Language Models lead by Noemí Merayo, Rosalía Cotelo, and Rocío Carratalá-Sáez, whose e-mail address are as follows:

noemer@uva.es

rosalia.cotelo@uam.es

rocio.carratala@uv.es

## Cite

We have recently subimtted a scientific article to Information Processing and Management journal presenting this corpus and the results derived from the execution of the scripts that leverage different GPT-4 models to process polarity and emotions.

## License

CORPUS-TLOU-DIALOGUES © 2026 by Noemí Merayo, Rosalía Cotelo, Rocío Carratalá-Sáez is licensed under Attribution-NonCommercial-ShareAlike 4.0 International 
