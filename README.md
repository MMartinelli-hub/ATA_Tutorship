# Folder Structure
- **bert_overview**: a jupyter notebook which provides an overview of BERT, including: tokenizer, padding, attention mask, architecture, native BERT tasks
- **bert_sequence_classification**: contains two notebooks that performs sequence classification using BERT. Includes two configurations: one with the classification head implemented from scratches, and one which uses the classification head built-in within the *transformers* library
- **ate_it**: various implementations for subtask A of ATE-IT shared task. Covers the following approaches:
    - nltk and spacy, zero-shot and trained
    - bert for token classification (with *transformers* built-in classification head and BIO tagging schema)
    - llm zero-shot classification (ATE-IT baseline)
    - llm prompt-optimized classification (using DSPy)
    - llm LORA fine-tuned classification (using unsloth)

# TODO (ranked by descending priority)
- Implement ATE-IT task B: term clustering 
- Implement NER and RE for GutBrainIE
- Implement BERT ensembling for token classification
- Implement sequence classification for MultiPride EvalITA shared task
- For LLM-based methods, add support for:
    - Azure
    - Groq
    - OpenAI
    - Local Ollama
    - Local Ollama on Google Colab
- Synthetic data generation