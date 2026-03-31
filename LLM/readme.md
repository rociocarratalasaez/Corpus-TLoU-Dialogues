Collection of scripts to:

1. Preprocess the TLoU dialogues included in the corpus (data_preparation.ipynb).

2. Execute the different GPT4 LLM (fine-tunning) to classify emotions and polarity.

  Note that, in the emotions/polarity scripts, it is necessary to add the OpenAI Platform API key in the "Fine-tuning process execution" section where needed:

  openai.api_key= # <----------- Add your key
  client = OpenAI(api_key= ) # <----------- Add your key

  Moreover, also in the emotions/polarity scripts, in the "Fined-tuned model verification" it is necessary to add the job ID where needed:
  
  model_idi= # <----------- Add your job ID
