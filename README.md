# Folder Structure
- **bert_overview**: a jupyter notebook which provides an overview of BERT, including: tokenizer, padding, attention mask, architecture, native BERT tasks
- **bert_sequence_classification**: contains two notebooks that performs sequence classification using BERT. Includes two configurations: one with the classification head implemented from scratches, and one which uses the classification head built-in within the *transformers* library
- **ate_it**: various implementations for subtasks A and B of ATE-IT shared task. Covers the following approaches:
    - nltk and spacy, zero-shot and trained
    - bert for token classification (with *transformers* built-in classification head and BIO tagging schema)
    - llm zero-shot classification (ATE-IT baseline)
    - llm prompt-optimized classification (using DSPy)
    - llm LORA fine-tuned classification (using unsloth)
    - term clustering based on similarity and k-means