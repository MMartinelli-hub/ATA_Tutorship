# Folder Structure
- **bert_overview**: a jupyter notebook which provides an overview of BERT, including: tokenizer, padding, attention mask, architecture, native BERT tasks
- **ate_it**: various implementations for subtasks A and B of ATE-IT shared task. Covers the following approaches:
    - nltk and spacy, zero-shot and trained
    - bert for token classification (with *transformers* built-in classification head and BIO tagging schema)
    - llm zero-shot classification (ATE-IT baseline)
    - llm prompt-optimized classification (using DSPy)
    - llm LORA fine-tuned classification (using unsloth)
    - term clustering based on similarity and k-means
- **gutbrainie**: various implementations for subtask 6.1 (Named Entity Recognition) and 6.2.3 (Mention-level Relation Extraction) of GutBrainIE-2025 shared task. Covers the following approaches:
    - vanilla NER 
    - bert for token classification (with *transformers* built-in classification head and BIO tagging schema)
    - GLiNER V1 and V2

## Note
- The **data** folder within **gutbrainie** is provided empty. You can download related files and populate this folder from: https://zenodo.org/records/16845409/files/GutBrainIE_Full_Collection_2025.zip?download=1
- The GLiNER implementation provided for GutBrainIE is developed for demonstrational purposes only. For a complete implementation specifically tailored to the NER subtask within GutBrainIE, please refer to the baseline system implementation provided by the GutBrainIE organizers at: https://github.com/MMartinelli-hub/GutBrainIE_2025_Baseline
